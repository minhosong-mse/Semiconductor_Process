# 🚗 Optimization of NMOS for Automotive Applications (TCAD)

### 📌 Project Overview
- **Goal:** 고온 환경(423K)에서 발생하는 차량용 NMOS의 구동 열화 현상을 공정 파라미터 최적화를 통해 해결.
- **Period:** 2026.04 ~ 2026.06
- **Keywords:** Automotive Semiconductor, NMOS, High-Temperature Degradation, TCAD, Reliability

### 🛠 Tools & Tech
- **Simulation:** TCAD (Synopsys or Sentaurus)
- **Key Techniques:** Halo/LDD/P-well Implantation, SS(Subthreshold Swing) Improvement

### 🎯 Key Challenges & Solutions
1. **Challenge:** 고온(423K) 환경에서 $I_{off}$ 누설 전류 급증 및 게이트 제어력(SS) 악화.
2. **Process Optimization:**
   - **Halo Doping:** Punch-through 및 공핍층 확장 억제.
   - **LDD (Lightly Doped Drain):** S/D 인근 피크 전계 완화.
   - **P-well Adjustment:** 도핑 최적화를 통한 누설 억제.

### 📈 Results
- **SS (Subthreshold Swing):** 1015.2 → 198.6 mV/dec (**80.4% 감소**)
- **$I_{off}$ Leakage:** 2.81E-05 → 1.58E-12 (대폭 억제)
- **$I_{on}/I_{off}$ Ratio:** 23 → 1.39E+08 (스위칭 안정성 회복)

### 📄 Documentation
- [반도체집적공정_기말프로젝트_보고서.pdf](https://github.com/minho031207/프로젝트저장소이름/blob/main/반도체집적공정_기말프로젝트_8조.pdf)
