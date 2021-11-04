# Rails AntiPatterns:  Best Practice Ruby on Rails Refactoring


## Chapter 1

### 
*  Law of demeter
	* Each unit should have only limited knowledge about other units: only units "closely" related to the current unit.
    *  Each unit should only talk to its friends; don't talk to strangers.
   *  Only talk to your immediate friends.
*  Push All find() Calls into Finders on the Model
*  Keep Finders on Their Own Model
