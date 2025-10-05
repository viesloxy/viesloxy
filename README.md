## Hi! I'm Veeto

```typescript
class InformaticsEngineering {
    public readonly name = "Vito Aditya"
    public major = "Informatics Engineering"
    public roles = ["Product Designer", "Web Development Enthusiast"]
    public languages = ["id_ID", "en_US"]
    public techStack = ["HTML", "CSS", "JavaScript", "TypeScript", "React", "Figma"]

    sayHello() {
        console.log("Hi 👋! I'm Vito Aditya — a Product Designer and Web Development Enthusiast passionate about creating meaningful digital experiences.")
    }

    learnTechStack(tech: string) {
        this.techStack.push(tech)
        return this
    }

    learnLanguage(lang: string) {
        this.languages.push(lang)
        return this
    }
}

const me = new InformaticsEngineer()
me.sayHello()

me.learnTechStack("Next.js").learnTechStack("Node.js")
```

![visitors](https://visitor-badge.laobi.icu/badge?page_id=viesloxy)
