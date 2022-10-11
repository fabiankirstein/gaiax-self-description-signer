# Gaia-X Self-Description-Signer (Java)

This is a port of this project to Java:
https://github.com/deltaDAO/self-description-signer/  
Please refer to the original repo for general information. 
This port currently only support the signing of self-descirptions.

## Requirements
- JDK >= 11
- Maven 

## Usage
- Build the Java application
```
& mvn clean package
```
- Create a self-description
```
& cp self-description.sample.json self-description.json 
```
- Create a config file
```
& cp config.sample.yaml config.yaml 
```
- Adjust self-description and config to your needs.
- Execute the signing process.
```
& java -jar target\self-description-signer-1.0.0-SNAPSHOT-fat.jar
```
If successful, you will find your timestamped DID, self-signed self-description and a complete self-description 
signed from the compliance service in the output directory. 

## Roadmap
- Add support for other Gaia-X artefacts
- Increase Usability
- Provide Docker Image
- ...










