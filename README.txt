MBS538 Lucky Draw - corrected Firebase connection

1. Firebase Console > Firestore Database > Rules: replace all rules with firestore.rules and Publish.
2. Firebase Console > Authentication > Sign-in method: enable Anonymous.
3. In GitHub repository tempa505/LuckyDraw, replace ROOT index.html with the index.html in this ZIP. Commit changes.
4. Wait for GitHub Pages deployment and open https://tempa505.github.io/LuckyDraw/
5. Test in two separate browser sessions before inviting participants. WARNING: A successful claim is permanent in the website; only Firebase project administrator can delete the document to reset.

Important: anonymous sign-in prevents duplicate claims per anonymous UID and repeated name strings, but does not verify real identity; someone could enter a different name in another browser. All topics are mapped by box number in code. This is for a small trusted group, not a secure lottery.
