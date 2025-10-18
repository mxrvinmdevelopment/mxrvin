<!-- mxrvin/mxrvin -->

<h1 align="center">👋 Hey, I'm Marvin</h1>
<h3 align="center">💻 Backend Developer | Python • C# • C++ | Security Enthusiast</h3>

---

### 🧠 About Me
I'm **Marvin**, also known as **mxrvin** a passionate backend developer focused on creating **robust, scalable server-side systems**.

- 🧩 Specialized in **Python**, **C#**, and **C++**
- 🧱 Building **clean, maintainable architectures**
- 🔐 Passionate about **security & ethical hacking**
- 📱 Exploring **Android development**
- 🚀 Always learning, coding, and improving

---

### ⚙️ My Tech Stack

#### 🧠 Backend
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?logo=c-sharp&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)

#### 🎨 Frontend
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

#### 🔐 Security & Mobile
![Ethical Hacking](https://img.shields.io/badge/Security-Ethical%20Hacking-red)
![Android](https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=white)

---

### 🧩 Projects & Code
🔗 Check out my work:
- 💡 [Portfolio Website](https://soon.com)
- 🧰 [GitHub Repositories]([https://github.com/mxrvin?tab=repositories](https://github.com/mxrvinmdevelopment?tab=repositories))

---

### 🧮 Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=mxrvin&show_icons=true&theme=radical" alt="mxrvin stats"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=mxrvin&theme=radical" alt="GitHub Streak"/>
</p>

---

### 🧑‍💻 Code Sample

```cpp
#include <iostream>
#include <vector>
#include <string>

class Developer {
public:
    std::string name;
    std::string role;
    std::vector<std::string> skills;

    Developer() {
        name = "Marvin";
        role = "Backend Dev";
        skills = {"Python", "C#", "C++"};
    }

    void showInfo() {
        std::cout << "Name: " << name << std::endl;
        std::cout << "Role: " << role << std::endl;
        std::cout << "Skills: ";
        for (const auto& skill : skills) {
            std::cout << skill << " ";
        }
        std::cout << std::endl;
    }
};

int main() {
    Developer marvin;
    marvin.showInfo();
    return 0;
}
