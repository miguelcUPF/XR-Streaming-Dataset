# XR Content Streaming over Wi-Fi: Traffic Characterization and Experimental Evaluation

This repository contains the datasets collected in the study, encompassing network traffic traces and WebRTC statistics for both the client and server. It also contains the script for analyzing the data.

## Folders

- **Datasets**: Contains various datasets collected from the server and client.
- **Scripts**: Contains the Python script for retrieving the dataset files from Google Drive. Includes the parsing, analysis, and visualization of the data records.

## Datasets

| Dataset | Name          | Characteristics                                                 |
|---------|---------------|-----------------------------------------------------------------|
| D1      | Baseline      | AH \| C: H.264, F: 90, R: 3664x1920p, B: 50 \| A: 0 \| Laptop   |
| D2      | Frame Rate    | AH \| C: H.264, F: 60 & 30, R: 3664x1920p, B: 50 \| A: 0 \| Laptop |
| D3      | Codec         | AH \| C: VP9, F: 90 & 60 & 30, R: 3664x1920p, B: 50 \| A: 0 \| Laptop |
| D4      | Resolution    | AH \| C: H.264, F: 90, R: 2880x1600p, B: 50 \| A: 0 \| Laptop     |
| D5      | Bitrate       | AH \| C: H.264, F: 90, R: 3664x1920p, B: 100 \| A: 0 \| Laptop    |
| D6      | ITK           | ITK \| C: H.264, F: 90, R: 3664x1920p, B: 50 \| A: 0 \| Laptop    |
| D7      | ER            | ER \| C: H.264, F: 90, R: 3664x1920p, B: 50 \| A: 0 \| Laptop     |
| D8      | Background    | AH \| C: H.264, F: 90, R: 3664x1920p, B: 50 \| A: 50 & 100 & 200 \| Laptop |
| D9      | Smartphone    | AH \| C: H.264, F: 90, R: 3664x1920p, B: 50 \| A: 0 \| Smartphone |
| D10     | Oculus        | AH \| C: H.264, F: 90, R: 3664x1920p, B: 50 \| A: 0 \| Laptop + Oculus Link |

AH: Alteration Hunting, ITK: Interaction Toolkit, ER: Escape Room, C: video codec, F: frame rate, R: resolution, B: bitrate, A: additional traffic.
