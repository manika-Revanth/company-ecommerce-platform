This the Version:2.0

WELCOME TO COMPANY-E-COMMERCE-PLATFORM APPLICATION!

this app contains files of 


company-ecommerce-platform/
│
├── README.md >> contains instructions to access the application
├── src/      >> contains the login,checkout,products pages
│   ├── index.html
│   ├── login.html
│   ├── products.html
│   └── checkout.html
│
├── config/  >> contains application configuration files
│   └── application.conf
│
├── docs/  >> gives you the overall structure of the application
│   └── architecture.md
│
└── logs/ >> contains log files

Branching Statergy:

main
  │
  ├── production
  │
  └── release branches

develop
  │
  ├── feature branches
  ├── bugfix branches
  └── integration


Rules:
1.main represents production.
2.develop represents ongoing development.
3.Developers must never directly develop features on main.
4.Features must be developed through feature branches.
5.Production fixes must use a hotfix workflow.

