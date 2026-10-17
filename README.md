<h1 align="center">Hi, I'm 이나경 (Na-Kyung Lee) 👋</h1>

<h3 align="center">Digital HW Design Engineer · RTL Design / SoC Integration / UVM Verification</h3>

<p align="center">Computer Architecture와 AI Accelerator 연구 경험을 바탕으로, 시스템을 하드웨어 구조로 구현하는 설계 엔지니어를 목표로 하고 있습니다.</p>

---

### 🔍 About Me

숭실대학교 전자정보공학부 IT융합전공에서 컴퓨터구조와 AI 가속기 / 시스템 아키텍처를 공부했으며, ISAC Lab 학부연구생으로 DNN의 메모리 오류 내성(Bit-Flip Fault Injection, Error Tolerance)을 분석하고 경량 오류 보호 기법 **FeatherGuard**(SCIE 제2저자, 한국·PCT·미국 특허 출원 참여) 연구에 참여했습니다.

이후 「온디바이스 AI 시스템반도체 설계 2기」(대한상공회의소 서울기술교육센터, 980H)에서 Verilog/SystemVerilog 기반 RTL 설계, AMBA IP 설계, FPGA 기반 HW/SW 통합 SoC와 UVM 기능 검증을 수행하며, 설계와 검증을 함께 이해하는 역량을 쌓았습니다.

### 🛠️ Skills

**RTL Design & Verification**
- Verilog · SystemVerilog · UVM · Functional Coverage · STA
- AMBA (AXI4 / AXI4-Lite / APB4) · UART · SPI · I²C

**FPGA & Embedded**
- Xilinx Vivado · Zybo Z7-20 · Basys 3 · MicroBlaze SoC
- STM32 (bare-metal) · Jetson Orin Nano · Arduino

**Tools & Languages**
- C · Python · Linux
- Notion · Git

### 📌 Featured Projects

**SoC / RTL Design**
- **[CNN Accelerator · DMA 기반 Vision Teleoperation SoC](https://2nak0.notion.site/3db6de42f579803da1acc6042436a6de)** — Zybo Z7-20에 INT8 Systolic Array CNN 가속기와 DMA를 통합해 카메라 영상의 조향각을 4.50 ms에 추론하는 Vision AI SoC. 팀장으로서 CNN 제어부 FSM 설계, Top 통합, UVM 검증 담당 (팀 프로젝트)
- **[AXI4-Lite 기반 Custom IP 설계 및 SoC 통합](https://2nak0.notion.site/3b06de42f579808f8820f903dcb7ba27)** — AXI4-Lite Custom Peripheral IP를 RTL로 설계하고 MicroBlaze SoC에 통합, HW/SW 제어 및 UVM 검증까지 수행
- **[RISC-V Single/Multi Cycle CPU](https://2nak0.notion.site/3c26de42f5798095911ad6db93b3684f)** — RV32I 기반 Single-cycle / Multi-cycle CPU 설계 및 FPGA 구현
- **[FPGA 기반 비접촉 패턴 인증 보안 홈캠](https://2nak0.notion.site/3e36de42f579807a8b2df9bd037135fc)** — Basys 3 FPGA 2대와 OV7670을 이용한 패턴 인증·영상처리 시스템. 팀장으로서 UART 제어 인터페이스, Top 통합, 시나리오 시뮬레이션 담당 (팀 프로젝트)

**Verification**
- **[APB4 Verification IP 설계 및 UVM 검증](https://2nak0.notion.site/3c66de42f579801fbc9df3ef518a4344)** — AMBA APB4 프로토콜 VIP 설계 및 UVM 검증 환경 구축
- **[SPI·I2C 통신 시스템 설계 및 UVM 검증](https://2nak0.notion.site/3c36de42f579805ab27fe6af86971c20)** — SPI / I²C Master-Slave RTL 설계 및 UVM 기반 기능 검증
- **[UART·FIFO·Sensor 기반 FPGA 디지털 시스템 설계](https://github.com/ky0nq/UART_FIFO_SENSOR)** — UART, FIFO, 센서 인터페이스를 통합한 FPGA 디지털 시스템 ([SystemVerilog 검증](https://github.com/ky0nq/UART_FIFO_DECODER_SV))

**Embedded & Edge AI**
- **[STM32 기반 Joystick 활용 게임기](https://2nak0.notion.site/3b06de42f57980c88299e37d5bb2f09e)** — STM32F4 bare-metal 펌웨어로 조이스틱, UART, LCD, 부저, RGB LED를 통합한 듀얼 게임기
- **[Jetson Orin Nano 기반 On-Device AI 차량 안전 모니터링 시스템](https://2nak0.notion.site/3c86de42f5798094a0bac69a346c1db6)** — 주행 중 안전벨트·졸음 감지 및 시동 종료 후 잔류 아동·반려동물 감지 (팀 프로젝트)

**Undergraduate**
- **[MLP 병렬 추론 시스템 최적화](https://2nak0.notion.site/3c86de42f579818c91f9d4b925aef9ec)** — 2025 프로젝트 보고서 챌린지(CPC) 장려상·인기상, 반도체공학회 하계종합학술대회 특별세션 발표
- **[Reconfigurable FIR Filter RTL 설계](https://2nak0.notion.site/3c86de42f57981e39fbdf4acd7c4f784)** — 재구성 가능한 FIR 필터 RTL 설계
- **[DNN 레이어·블록 단위 양자화에 따른 추론 정확도 경향성 분석](https://2nak0.notion.site/3c86de42f57981f8a58bf0c7eec2a364)** — 양자화 단위에 따른 DNN 추론 정확도 분석

👉 전체 프로젝트와 상세 내용은 [Notion Portfolio](https://app.notion.com/p/2nak0/Na-Kyung-s-Portfolio-4f66de42f57982d1998081ca1238769c)에서 확인하실 수 있습니다.

### 🏅 Awards & Publications

- **FeatherGuard** · Edge DNN을 위한 경량 오류 보호 기법 — 국외 SCIE 논문 제2저자 (2025.12), 한국·PCT·미국 특허 출원 참여
- 온디바이스 AI 프로젝트 발표회 최우수상 (2026.10)
- 2025 프로젝트 보고서 챌린지(CPC) 장려상·인기상 (2025.09)

### 📫 Contact

- 📧 Email: iidrabbii@naver.com
- 📄 Resume: [2nak0.notion.site/soc-rtl-design-verification](https://2nak0.notion.site/soc-rtl-design-verification)
- 📝 Blog: [ky0nq.tistory.com](https://ky0nq.tistory.com/)
- 🎬 YouTube: [@nak0-4](https://www.youtube.com/@nak0-4)
- 💻 GitHub: [github.com/ky0nq](https://github.com/ky0nq)

---
