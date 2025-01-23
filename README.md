# Real-time-noise-cancelation
# Audio Processing System with Noise Reduction

## **Project Description**
This project involves developing a real-time audio processing system capable of noise reduction for both single and multi-speaker scenarios. The system processes audio streams in real time using filters and has functionalities for saving processed audio, adapting to different scenarios, and testing. Future improvements include integrating advanced noise cancellation techniques and automatic scenario detection.

---

## **Features**
1. **Real-Time Audio Processing**:
   - Captures and processes audio streams in real time.
   - Reduces noise for single or multi-speaker scenarios.

2. **Scenarios**:
   - **Single Speaker:** Applies noise reduction for individual speakers.
   - **Multi-Speaker:** Handles audio with multiple speakers using advanced filtering.

3. **Saving Processed Audio**:
   - Allows saving the processed audio to WAV files for further analysis or playback.

4. **Dynamic Adaptability** (Future Scope):
   - Automatic identification of single or multi-speaker scenarios.
   - Advanced noise reduction using libraries like PyTorch, librosa, or pre-trained models.

5. **Unit Testing**:
   - Ensures functionality and reliability with pre-written test cases.

---

## **Requirements**
- Python 3.8+
- Libraries:
  - `pyaudio`
  - `wave`
  - `numpy`
  - `unittest`

---

## **Usage**
### **Running the Application**
1. Run the main audio processing script:
   ```bash
   python main.py
   ```

2. Follow the prompt to select a scenario:
   - **Single:** For single speaker noise reduction.
   - **Multi:** For multiple speakers.

3. The system will process audio in real-time and save the output to `output/processed_audio.wav`.

### **Example Command**
```bash
python main.py
```
Select scenario: single
Captured audio chunk: [123, 456, ...]  
Processed audio saved to: `output/processed_audio.wav`


## **How It Works**
1. **Audio Stream Initialization**:
   - Input and output audio streams are initialized using PyAudio.

2. **Audio Filtering**:
   - Captures audio chunks and applies filters based on the selected scenario (single or multi-speaker).
   - Noise cancellation is implemented as a placeholder logic (gain/noise reduction).

3. **Processed Audio Saving**:
   - After filtering, processed audio chunks are saved as WAV files for further use.

4. **Unit Testing**:
   - Validates the functionality of single and multi-speaker filters to ensure accuracy and reliability.

---

## **Future Enhancements**
1. **Automatic Scenario Detection**:
   - Incorporate algorithms to automatically detect single or multi-speaker scenarios.

2. **Advanced Noise Cancellation**:
   - Integrate pre-trained models and libraries (e.g., librosa, Demucs, or PyTorch) for more effective noise reduction.

3. **Improved Real-Time Performance**:
   - Optimize processing speed and scalability for larger applications.

4. **UI Integration**:
   - Add a graphical interface for easier scenario selection and audio visualization.

---


#
