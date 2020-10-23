# This is a Copyright smart contract marketplace

This smart contract stores licences that people create for their content that's identified by a Unique ID, all on the Ethereum blockchain. 

Here is the way copyright law works in simple terms:

1. You register a piece of content that could be a document, text, an image, a video, or any kind of creation that you did by yourself with a unique identifier, publicly so that people can confirm your authority.

2. The people that want to use your content for whatever reasons have to consult
your copyright terms and obey them to avoid legal problems, because we don't
want people stealing your work for their own benefit.

A copyrighted register shouldn't be modified, so we will avoid creating functions that allow people to modify their copyrighted data; so, we'll only allow them to add or remove copyrights.

This smart contract has the following functions:
  * A function to add new copyrighted content with a unique identifier that you create by hashing the content.
  * A function to get content based on a hash.
  * A function to delete copyrighted content if you're the owner.
  * A function to extract the funds locked in the smart contract.
