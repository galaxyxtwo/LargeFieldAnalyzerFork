# LargeFieldAnalyzer WIP


Login at [Leto.gg](https://leto.gg) and upgrade to a business plan for access to the Large Field Analyzer for Malware detection. Reach out to admin@galaxyx.io for questions or a free trial!

<img width="1418" alt="AnalyzerPass2" src="https://github.com/galaxyxtwo/LargeFieldAnalyzerFork/assets/90220293/50e452a4-90a4-46a3-af60-fd72253805be">


Currently there are two ways Leto can scan content for malware. 
- Input an IPFS CID into our Analyzer Dashboard (either a CID or URL Address). To scan your content for malware, the content needs to be publically retrievable by our system.
- Input a csv file with a list of CIDs or URL Addresses). Leto will scan each file and send the user an email with a malware risk report for the files.

Important Malware Analyzer Repos:
- Front end for the Leto Dashboard - https://github.com/Leto-gg/dashboard
- Leto Auth - https://github.com/Leto-gg/dev-leto-auth
- Leto API - https://github.com/Leto-gg/dev-leto-api
- Backend Analyzer Relay running on the Leto node to move data to the analyzer sandbox - https://github.com/noryev/DatabaseSync/tree/main
- Add files to MongoDB - https://github.com/noryev/AnalyzerRelay/tree/main
