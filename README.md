임베디드 First
----------
# 1. 임베디드 시스템의 정의
임베디드 시스템은 특정 기능을 수행하기 위해 설계된 하드웨어와 소프트웨어의 결합체로, 대량 생산 제품에 내장되어 특별한 목적을 수행하는 시스템입니다. 예를 들어 스마트폰, 의료기기, 로봇 청소기 등이 대표적인 임베디드 시스템입니다​.

# 2. 임베디드 시스템의 특징
* 특정 목적 수행: 일반적인 컴퓨터와 달리, 임베디드 시스템은 특정 작업이나 기능을 수행하는 데 최적화되어 있습니다​.
* 하드웨어와 소프트웨어 결합: 하드웨어와 소프트웨어가 밀접하게 연관되어 있어 시스템 내에서 강력한 상호작용을 요구합니다​.
* 실시간 처리: 대부분의 임베디드 시스템은 즉각적인 응답과 실시간 처리를 필요로 합니다. 예를 들어 의료기기나 자동차 시스템은 실시간으로 데이터를 처리해야 합니다​.
# 3. 임베디드 시스템의 구성 요소
* 하드웨어: CPU, 메모리, 입출력 포트 등의 기본 컴퓨터 구성 요소들이 사용됩니다. 마이크로컨트롤러(MCU)나 시스템 온 칩(SoC)이 핵심 요소로 사용됩니다​.
* 소프트웨어: 임베디드 소프트웨어는 하드웨어를 제어하며, 범용 소프트웨어와 달리 하드웨어 제어를 중심으로 설계됩니다​.

# 4. 응용 분야
* 소비자 가전: TV, 로봇 청소기, 세탁기 등 다양한 가전제품에서 임베디드 시스템이 사용됩니다.
* 자동차: 차량의 엔진 제어 시스템, ECU, 자율 주행 기능 등을 포함합니다​.
* 의료 기기: 심박계, 인공호흡기 등 실시간으로 환자 데이터를 수집하고 제어하는 의료 장치에서 사용됩니다​.
* 통신 장치: 스마트폰, IoT 기기 등에서 다양한 기능을 처리하는 역할을 수행합니다​.
# 5. 임베디드 시스템의 장단점
#### 장점
+ 저전력 소비: 마이크로컨트롤러나 SoC 기반 시스템은 일반적으로 낮은 전력 소비를 통해 배터리로 동작하는 장치에 적합합니다.
+ 비용 효율성: 대량 생산과 특정 작업에 최적화된 설계로 인해 비용이 낮고, 소형화된 설계가 가능합니다.
+ 특정 목적에 최적화: 임베디드 시스템은 각 애플리케이션에 맞게 최적화되어 성능과 안정성이 높습니다​.
#### 단점
+ 확장성 부족: 특정 기능에 최적화되어 있어, 범용 시스템에 비해 확장성이나 유연성이 부족할 수 있습니다​.
+ 리소스 제한: 메모리, 처리 성능이 제한되어 있어 복잡한 소프트웨어나 작업을 처리하기 어려울 수 있습니다​.
# 6. 미래 전망
임베디드 시스템은 IoT(사물 인터넷)의 성장과 함께 더욱 확장될 전망입니다. 특히 5G 통신 기술과 결합되어, 실시간 데이터 처리와 저전력 고성능 시스템이 더 많이 요구될 것입니다. 
또한, 인공지능(AI)을 기반으로 한 스마트 기기와 자율 시스템의 개발이 임베디드 시스템의 미래를 밝게 하고 있습니다​.
임베디드 시스템의 복합성과 성능이 지속적으로 향상됨에 따라, 그 적용 범위는 더 넓어지고, 스마트 홈부터 자율 주행차까지 다양한 산업에 걸쳐 중요한 역할을 할 것입니다.

***

- MCU(Microcontroller) - CPU,메모리,I/O포트 를 단입칩에 통합한 소형 컴퓨터입니다. 특정 작업 수행에 최적화 되어있으며 상대적으로 낮은 전력을 소비합니다. 또한 간단한 소프트웨어로 실행되며 비용이 낮고 단순하고 효율적인 설계가 가능합니다. (Arduino)
* SOC(System on Chip) - 하나의 칩에 CPU, 메모리, I/O포트 뿐 아니라 GPU, DSP, 모뎀, 보안모듈, 인터페이스 등 복잡한 시스템 구성요소를 담은 시스템입니다. MCU보다 다수의 작업을 동시에 수행할 수 있으며 고성능을 제공하여 비용과 전력이 더 많이 소비됩니다. (Raspberry Pi)
