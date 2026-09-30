# maritime-collision-avoidance-ai
AI-powered collision avoidance for maritime vessels               using YOLOv8 vision detection and AIS data fusion
# Maritime Collision Avoidance AI

## Overview
AI-powered collision avoidance system for maritime vessels using YOLOv8 
object detection and AIS data fusion.

**Performance:** 96% F1-score, 34 fps real-time processing on NVIDIA Jetson

## Problem Statement
Millions of smaller vessels (barges, fishing boats, tugs) operate without 
AIS tracking. Current maritime surveillance systems miss these "dark targets," 
leading to collision risks in congested waters.

## Solution
Fusion-based detection combining:
- **YOLOv8 OBB**: Real-time vessel detection via camera feeds
- **AIS Integration**: WebSocket stream of vessel tracking data
- **Spatial Reasoning**: Pixel-to-geographic coordinate mapping
- **Agentic AI**: Collision prediction and decision-making
- **Dashboard**: Streamlit visualization for operators

## Dataset
- Personal maritime photography: 20+ vessel images (various angles, weather)
- HRSC2016: 1000+ high-resolution ship detection images
- SeaShips: 1000+ satellite vessel images
- Total: 2000+ images for training

## Technical Stack
- YOLOv8 (object detection, oriented bounding boxes)
- NVIDIA Jetson (edge computing)
- Python 3.9+
- Streamlit (dashboard)
- WebSocket (AIS data ingestion)

## Results
| Metric | Value |
|--------|-------|
| F1-Score | 96% |
| Real-time FPS | 34 fps |
| Edge Device | NVIDIA Jetson |
| Weather Robustness | 79-93% (rain/fog) |

## Publications
- arXiv submission: December 2026
- Target venues: CVPR 2027, ICCV 2027

## Author
Victor Chen  
Chief Mate (Maritime) + M.S. Electrical Engineering  
Independent Maritime AI Researcher  
victor.cheng.wei@gmail.com  
[LinkedIn](https://linkedin.com/in/victor-chen-6b50371a2)

## License
MIT
