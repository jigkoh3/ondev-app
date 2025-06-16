# วิธีการใช้งาน Schemetic CLI สำหรับ Angular 
* 1. สร้างโปรเจคใหม่โดยการ download project template จาก 
```bash
https://gitlab211.cyberadvancesystem.com/casan/template/ng-nestjs-mongo-template/casan-fe-template.git
```
* 2. Install node package โดยใช้คำสั่ง 
```bash
npm i
```
* 3. ติดตั้ง CASAN Schemetic CLI โดยใช้คำสั่ง 
```bash
npm i --save-dev casan-schematics
```
* 4. Generate Angular services โดยใช้คำสั่ง 
```bash
schematics casan-schematics:fuse-crud-services --name=diagnose
```
* 5. Generate Angular components โดยใช้คำสั่ง 
```bash
schematics casan-schematics:fuse-crud-components --name=diagnose
```
