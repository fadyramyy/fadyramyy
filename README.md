## Hi There 🌟

```python
#!/usr/bin/python
# -*- coding: utf-8 -*-


class Developer:

    def __init__(self):
        self.name = "Fady Ramy"
        self.role = "CS / Software Engineering Student"
        self.location = "Egypt"

        self.languages_spoken = ["Arabic (Egypt)", "English"]

        self.programming_languages = [
            "Python",
            "C++",
            "JavaScript",
            "SQL"
        ]

        self.focus = [
            "Machine Learning",
            "Data Analysis",
            "Software Engineering",
            "Building practical projects"
        ]

        self.tools = [
            "pandas",
            "NumPy",
            "scikit-learn",
            "Streamlit",
            "Git",
            "GitHub",
            "VS Code"
        ]

    def hi(self):
        print(f"Hi, I'm {self.name}.")
        print(f"{self.role} based in {self.location}.")

    def currently(self):
        print("Currently turning notebooks into clean, usable projects.")

    def stack(self):
        print("\nProgramming languages:")
        for language in self.programming_languages:
            print(f"- {language}")

        print("\nFocus:")
        for item in self.focus:
            print(f"- {item}")

        print("\nTools:")
        for tool in self.tools:
            print(f"- {tool}")


me = Developer()

me.hi()
me.currently()
me.stack()
```

### Find me elsewhere

- LinkedIn: www.linkedin.com/in/fady-ramy-757507369
- Email: fadyramy2006@gmail.com
