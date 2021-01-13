## Suricata Rules

## Process
1. `test.rules`에서 Suricata rule 생성
2. `sudo tail -f /var/log/suricata/fast.log`
3. `sudo suricata -s test.rules -i ens33`
    - `fast.log`와 다른 터미널 창에서
4. 룰에 있는 사이트에 접속하면서 `fast.log`에서 로깅 확인

