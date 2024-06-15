# Freecodecamp - Desenvolvimento Backend

## Managing Packages With npm

### Semantic Versions

```json
{ 
    "dependencies": {
		"express": "^4.14.0",
		"@freecodecamp/example": "^1.2.13"
	},

}
```

- "express" : "~MAJOR.MINOR.PATCH": Permite Atualizações de bugs Qualquer versão do mesmo nível Ex.: 1.2.x

- "express": "^MAJOR.MINOR.PATCH": Permite atualizações de novas features e correções de bugs Ex.: 1.x.x

- Quando não tem nada, ^ ou ~ é uma versão fixa