# Typescript-cheat-sheet

## How to Run TypeScript 
**This one will convernt TS to JS:** tsc fileName.ts \
**If we want to monitor TS change Realtime then:** tsc fileName.ts --watch \

## Variable in TS
**String =:** let firstName: string = "Zulkar Nayin"; \
**Number =:** let studetnId: number = 2314; \
**Boolean =:** let isActive: boolean = true; \
**Any =**: let bjit: any = "Software Company"; \
**Array:** let studentList: any[] = ["zulkar", 463]; \
**Unit Type =:** let studentList: (string | number)[] = ["zulkar", 463]; 

### Tuple
let arr: [string, number] =["zulkar Nayin", 16303045] \

## Enum
Reference: https://www.typescriptlang.org/docs/handbook/enums.html#handbook-content \
Type: \
string \
numeric \
Heterogeneous \
example: enum RollType {STUDENT, ADMIN, TEACHER} \
        let WhichROll: RollType

## Object
let students: object; \
let student: {name: string, id:number}; \
let student: {name: string, id?:number}; //? sign for keep optional \
let student: object[]; //For store arry of object 
