Name: Muhanad Al-Rubaiee

Email: muhanad40@gmail.com

Time to complete: About 3 hours

Notes:
I used MobX because it's quick to set up and has less boilerplate code than Redux. Used Jest to drive my development. I didn't implement the drag and drop functionality because I've spent too much time on it.

I couldn't use Jest's `setupFiles` config because of create-react-app limitations so as a temporary workaround I imported a file that sets up the tests.

I usually use `babel-plugin-proposal-class-properties` but skipped it so I don't waste time fiddling around with build configs

Improvements:
- Could use `Array.prototype.reduce` to make the logic that counts the dietary types more functional
- Would tidy up the folder structure a bit. For example, store model and App are not in separate folders.
- Make the top left count copy singular and plural depending on count.
