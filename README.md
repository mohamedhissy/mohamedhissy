Hi there 👋, I'm Mohammed AlHissy:

I am a Full-Stack Developer with expertise in various languages and tools such as Laravel, PHP, Flutter, Dart, Android, Java, Python, HTML, CSS, Firebase, Refactoring, AWS, Linux, etc. I have experience in building various web and mobile applications.

    class DevMaas extends Developer
    {
        public String $name = "Mohammed AlHissy";
        public String $position = "Flutter Developer";
    
        public function knowledge()
        {
            return collect([
                "Laravel",
                "Flutter",
                "Android",
                "Java",
                "Python",
                "AWS",
                "Refactoring",
                "Linux",
            ]);
        }

        public function contacts()
        {
            return collect([
                "Email" => "mhmdalhsy49@gmail.com",
                "github" => "https://github.com/mohamedhissy", 
            ]);
        }
    }
