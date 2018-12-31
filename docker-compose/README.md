Docker Learning

"# รันโดยใช้คำสั่ง docker-compose up -d"


สรุป Dockerfile 

	Dockerfile คือ text document ที่ระบุวิธีการ และคำสั่งทั้งหมด ที่เอาไว้ประกอบร่าง Docker Image ขึ้นมา โดยใช้คำสั่ง docker build 
	
สรุป Docker Compose
 
    Docker Compose คือ สิ่งที่มาช่วย นำคำสั่งต่างๆ ของ Docker มาทำงาน พร้อมๆกันโดยมาเขียนในรูปแบบ yaml(yml) หรือที่อาจจะเรียกว่า Configuration File ที่อ่านง่ายกว่าที่จะเขียน bash script ยาวๆ ข้อดีของ Docker Compose นั่นก็คือ เราสามารถ Start / Stop / Restart / Log / Build Docker Container ได้โดยใช้คำสั่งบรรทัดเดียว และทำได้หลาย Container พร้อมๆกัน อาจถูกรวมมองเป็น Service ได้เลย