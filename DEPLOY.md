# Deployment Note

Due to environment restrictions with non-ASCII file paths, the new pages are located in the `smart_substation/pages` directory with English filenames.

## Mapping

| Original Request Name | New Filename |
|-----------------------|--------------|
| 周界安防感知 | perimeter_security.html |
| 入侵告警联动 | intrusion_alarm.html |
| 远程智能巡视 | remote_inspection.html |
| 智能预警中心 | smart_warning.html |
| 辅助决策分析 | decision_support.html |
| 实时状态监测 | realtime_monitor.html |
| 故障定位 | fault_location.html |
| 新能源调控 | renewable_control.html |
| 功率预测 | power_forecast.html |
| 用户权限 | user_permission.html |
| 操作日志 | operation_log.html |
| AI缺陷识别 | AI_defect.html |
| 光纤振动监测 | fiber_monitor.html |
| 线损分析 | loss_analysis.html |
| 通信网络 | comm_network.html |

Please ensure the main navigation in `smart-substation-system.html` (if any) is updated to point to these new locations/filenames, or rename them back to Chinese if your deployment environment supports it.
