![marcado 1](/img/banner%20github.png)


```python

    class ReadMe:

        def __init__(self, username="wils09", year=2023):
        
            self.username = username
            self.name = 'Cris Coradini'
            self.education = { 
                'programming': ['Full Stack web developer','ISPC' ]
            }
            self.code = {
                'frontend': ['HTML', 'CSS', 'JavaScript','Boostrap'],
                'backend': ['Python', 'java'],
                'database': [ 'MySQL', 'MariaDB'],
                'tools': ['GIT', 'GitHub', 'Githubdesktop'],
                'misc':'SCRUM'
            }
            self.project = {
                'backend' =  ['universidadGrupo25',  'andreaalonso727/ProveMaxGpo25'],
                'frontend' = ['TSDWAD2023com1grupo1/trabajointegradorgrup1']
            }
            self.employment = {
            'developer': ['company', 'city'],
            }

        def doing(self, now=2023):
            today = self.year

            if now < today:
                experience=self.project[backend]
                return """
                I was a backend dev in {project1} and {project2}
                """.format(project1=experience[0], project2=experience[1])

            elif now = today:
                dream = self.education['programming']
                return """
                I am currently learning {code} at {code_institute}.
                """.format(code=dream[0], code_institute=dream[1])

            elif now > today:
                goal = self.employment['developer']
                return """
                I am eager to collaborate with {teams} on {projects}.
                """.format(teams=goal[0], projects='web development')
            else:
                return """
                ### Hi there 👋🖥️🎧
                ✨✨✨✨✨
                """
        
        def collaborate(self, role, organization):
            opportunity = self.employment
            opportunity[role] = [organization]

    me = ReadMe(2023)    
```
You can find me📡:
- [linkedin](http://www.linkedin.com/in/criscoradiniprogramacion)
- [instagram](https://instagram.com/wilsoncris09)

 I love connecting with different people so if you want to say hi, I'll be happy to meet you more! :)
<!--


**wils09/wils09** is a  _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
