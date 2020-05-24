struct student{
    var name:String
    var rollno:Int
    var class_:Int
    func classdetail(){
        print("\(name) of class \(class_) have rollno is \(rollno) ")
    }
}
var student1 = student(name:"gaurav singh",rollno:14,class_:12)
student1.classdetail()