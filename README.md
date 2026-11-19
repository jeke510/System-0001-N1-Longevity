**System-0001-N1-Longevity** — Open-source N=1 longitudinal physiological dataset, sleep/HRV/gait metrics, and biohacking protocols for longevity science research (`System-0001`).

# System-0001: N=1 Longitudinal Health & Longevity Log

Personal longitudinal $N=1$ tracking dataset (age 65, `System-0001`), logging sleep architecture, autonomic/HRV metrics, physiological & movement markers, daily interventions, and body composition.

## Dataset Overview
- **File**: `weekly_log.csv`
- **Schema**: **36 columns** (`date` through `notes`, with `sunlight_min` as column 35 and `notes` as column 36).
- **Current Sample**: 19 aligned records spanning late October to mid-November 2026 (including pre-11/16 historical entries and post-11/16 daily entries).
- **Missing Values**: `NA` indicates unmeasured or unavailable metrics for that date/timepoint.

## Notes on Data Continuity & Alignment
- Dates in the early historical segment are non-continuous where logs were not saved.
- Walk and stool observations follow a `T-1` reporting convention starting around mid-November 2026.

---

# System-0001：个人 N=1 纵向健康与长寿追踪日志

65 岁个人 $N=1$ 纵向追踪数据集（编号 `System-0001`），记录睡眠结构、自主神经/HRV 指标、体能与动作状态、日常干预及躯体成分。

## 数据概览
- **主文件**：`weekly_log.csv`
- **表结构**：严格 **36 列**（从 `date` 到 `notes`，第 35 列为 `sunlight_min`，第 36 列为 `notes`）。
- **当前规模**：共 19 条对齐记录（覆盖 2026 年 10 月底至 11 月中旬，含 11/16 补录历史行及后续记录）。
- **缺失值规范**：未采集或当日无数据的字段统一填 `NA`，不作臆测补齐。

## 连续性与口径说明
- 早期历史记录因部分日期未保存，存在间断缺口，按实际保存日期升序排列。
- 11 月中旬起慢走与大便相关观察采用前一日（`T-1`）口径记录，跨期对比时请注意对齐。
