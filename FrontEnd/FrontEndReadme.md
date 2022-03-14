FrontEnd design with React.js

npm run dev 
^^ To start fake db.json server with react server
Db.json server in localhost:3001, react server in localhost:3000

APIs

//Submission API

// Front end send to backend
{
	name: String,
    query: String,
    timeStamp: DateTime,
    challengeId: Number,
}

//  backend to front end
{
	name: String,
    query: String,
    id: String,
    timeStamp: DateTime,
    challengeId: Number,
    planningTime: Number,
    executionTime: Number,
    isCorrect: Boolean,
}

// SQL Challenge
// Front end to backend
{
    challenge: String
}

//Backend to frontend
{
    challenge: String,
    challengeId: Number
}