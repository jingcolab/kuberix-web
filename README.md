# Kuberix — AI robotics training planning

English-language robotics training planning website for kuberix.tech. Static HTML/CSS/JavaScript; no build dependencies.

## Implemented
- Task, success and stop-condition specification.
- Six self-reported data/safety review checks; not an automatic audit or certification.
- Recording time, action/video sample counts, constant-bitrate video size and nominal split calculations.
- Locally generated JSON planning document and download; not an executable training config.
- Session-only by default, explicit local-storage opt-in with restore/removal, clear confirmation and unsaved-change protection.
- Keyboard-accessible tabs, responsive light/dark layouts; official LeRobot/MuJoCo resource links.

## Run and test
Serve with `python -m http.server 8000` and open http://localhost:8000. `npm test` runs pure-function tests on Node 20+; no dependency install needed.

## Hosting
Deploy as static files. No database, GPU, model API, auth provider, secret, payment or robot connection required. GitHub Pages can publish from main/root. Preserve CNAME once configured. Use HTTPS on production.

## Boundaries
No actual model training, dataset inspection/upload, simulation, robot control, cloud sync or safety authorization. Inputs are device-local; optional browser storage is not encrypted. Avoid sensitive information. No tracking scripts. Generated hero image is labeled as AI-generated editorial imagery.
