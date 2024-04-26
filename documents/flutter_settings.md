#### windows setting  
https://chocolatey.org/install  
https://docs.flutter.dev/get-started/install/windows/desktop?tab=download  
1. powershell관리자 실행후 아래 명령어 입력:    
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))   
 
2. choco install flutter    

3. flutter create flutter_study
