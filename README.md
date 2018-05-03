# naminator
Generates random names for servers, machines, hostnames, or other identifiers

Inspired by Docker, but uses cartographers as names.

## Usage

     ./naminator
     charming_davinci

Some examples:

    ber@sophie:naminator (develop) ☙ for i in $(seq 1 10); do echo "$i $(./naminator)"; done
    1 honest_alkhwarazmi
    2 sober_seco
    3 charming_roy
    4 patient_teixeira
    5 quiet_fowler
    6 kindly_vingboons
    7 dynamic_alkhwarazmi
    8 social_fawcett
    9 creative_rawat
    10 gallant_schmettau
   
## Security

The amount of names and adjectives is too low to work as proper password-generator, there's simply too little entropy.
So don't use it for things that cannot or should not be guessable.
