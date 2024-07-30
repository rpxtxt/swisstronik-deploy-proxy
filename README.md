### Swisstronik Tesnet Techinal Task Deploy Proxy


#### Clone Repository

```bash
git clone https://github.com/Mnuralim/swisstronik-deploy-proxy.git
```

```
cd swisstronik-deploy-proxy
```

#### Install Dependency

```
npm install
```

#### Set .env File

create .env file in root project

```
touch .env
```

add this to your .env file

```
PRIVATE_KEY="your private key"
```

#### Compile Smart Contract

```
npm run compile
```

#### Deploy Smart Contract

```
npm run deploy
```

#### Initialize Owner

```
npm run initialize
```

#### Add Issuer

```
npm run add-issuers
```

#### Get Issuers list

```
npm run list-issuers
```

#### Upgrade Smart Contract

```
npm run upgrade
```

#### Finsihed

- Open the deployed-adddress.ts file (location in utils folder)
- Select SWTRProxy
- Copy the address and paste the address into testnet dashboard(Point1)
- Open address-with-explorer.txt file (location in utils folder)
- Copy the address explorer and paste the address into testnet dashboard(Point2)
- Open tx-hash.txt file (location in utils folder)
- Copy the transaction hash link and paste the address into testnet dashboard(Point3)
- No need push to github