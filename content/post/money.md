---
date: 2017-03-30T12:17:09-04:00
title: money
---

I read the following books in 2017:
- 48 Laws of Power
- Mastery
- Grow and think rich
- Obstacle is the way
- Ego is the enemy
- Deep Work

~~~ruby

Pub1a:
  Type: AWS::EC2::Subnet
  Properties:
    VpcId: !Ref NuvopsVpc
    CidrBlock: 10.10.76.0/28
    AvailabilityZone: us-east-1a
    Tags:
      - Key: Name
        Value: Pub-1a-10.10.76.0

Priv1a:
  Type: AWS::EC2::Subnet
  Properties:
    VpcId: !Ref NuvopsVpc
    CidrBlock: 10.10.76.16/28
    AvailabilityZone: us-east-1a
    Tags:
      - Key: Name
        Value: Priv-1a-10.10.76.1

~~~


~~~python

import Musician from './liverpool';

class Paul extends Musician {
    constructor(bass) {
        super(bass);
    }

    get fullName() {
        return 'Paul McCartney';
    }

    perform() {
        this.play(this.instrument);
        this.sing();
    }
}

export default Paul;

~~~
