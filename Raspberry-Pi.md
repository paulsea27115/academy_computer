## Raspberry-Pi 주의사항
- HDMI선은 전원연결 전에 삽입
- ssd 카트 넣을때 전원 끄고 삽입

## SD Memory Crad Formatter link
- 링크 : https://www.sdcard.org/downloads/formatter/sd-memory-card-formatter-for-windows-download/

## Raspberry-Pi Imager link
- 링크 : https://www.raspberrypi.com/software/

## Raspberry-Pi 한글다운
   ```
   sudo apt-get -y update && sudo apt-get -y  upgrade
   
   sudo apt install -y fonts-unfonts-core
   
   sudo apt install ibus-hangul
   ```
## Raspberry-Pi Python3 다운
   ```
   sudo apt-get -y install python3-dev
   
   pip3 install opencv-python
   
   pip3 install opencv-contrib-python==4.1.0.25
   ```
   - 에러 발생시
   ```
   pip3 install opencv-contrib-python 
   
   sudo apt-get install -y libatlas-base-dev libhdf5-dev libhdf5-serial-dev libatlas-base-dev libjasper-dev  libqtgui4  libqt4-test
   ```
   - 또는
   ```
   sudo apt-get install libatlas-base-dev
   ```
