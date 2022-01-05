# 12-Factor App

The 12 Factor App ia a methodology to for building software as a service app that:

  1. Setup automation to minimize time and cost for making new developers life simple who are joining the project
  2. OS independent, offering maximum portability between execution environments
  3. Suitable for deployment on modern cloud platforms
  4. Minimize divergence between development and production, enabling continuous deployment for maximum agility
  5. And can scale up without significant changes to tooling, architecture, or development practices

The twelve-factor methodology can be applied to apps written in any programming language, and which use any combination of backing services

Following are the 12 Factors

  1.  Codebase: One codebase tracked in revision control, many deployments
  2.  Dependencies: Explicitly declare and isolate dependencies
  3.  Config: Store config in the environment
  4.  Backing Services: Treat backing services as attached resources
  5.  Build, release, run: Strictly separate build and run stages
  6.  Processes: Execute the app as one or more stateless processes
  7.  Port Binding: Export services via port binding
  8.  Concurrecy: Scale out via the process model
  9.  Disposability: Maximize robustness with fast startup and graceful shutdown
  10.  Dev / Prod parity: Keep development, staging, and production as similar as possible
  11.  Logs: Treat logs as event streams
  12.  Admin processes: Run admin/management tasks as one-off processes





Reference: https://12factor.net/

