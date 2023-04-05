
# 🖲 68 Flutter and Dart interview questions (answered) for mobile app developers

Flutter is leading the mobile app revolution. It won over every mobile technology and became the only choice for cross-platform app development. Follow along and check our list of essential Flutter interview questions and answers that will trend on mobile developers interviews in 2021.

</br>

<p align="center">
  <a href="https://devinterview.io/">
  <img src="https://source.unsplash.com/collection/52661698/600x300">
  </a>
</p>

</br>

> You can also find all 68 answers here 👉🏼 https://devinterview.io/dev/flutter-interview-questions

</br>

<div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 1. When to use main Axis Alignment and cross Axis Alignment?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><p><strong>For Row:</strong><br><code>mainAxisAlignment</code> = Horizontal Axis<br><code>crossAxisAlignment</code> = Vertical Axis</p><p></p><div><div><div><div></div></div></div></div><p></p><p><strong>For Column:</strong></p><p><code>mainAxisAlignment</code> = Vertical Axis<br><code>crossAxisAlignment</code> = Horizontal Axis</p><p></p><div><div><div><div></div></div></div></div><p></p><p><a href="https://flutter.dev/docs/development/ui/layout#aligning-widgets">Image source</a></p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://stackoverflow.com/questions/53850149/flutter-crossaxisalignment-vs-mainaxisalignment/53856933#53856933" rel="noreferrer" target="_blank" title="When to use main Axis Alignment and cross Axis Alignment? Interview Questions Source To Answer">stackoverflow.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 2. What is Flutter?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><p><strong>Flutter</strong> is an open-source UI toolkit from <em>Google</em> for crafting beautiful, natively compiled applications for desktop, web, and mobile from a single codebase. Flutter apps are built using the <em>Dart</em> programming language.</p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://flutter.dev" rel="noreferrer" target="_blank" title="What is Flutter? Interview Questions Source To Answer">flutter.dev</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 3. What is the difference between Expanded and Flexible widgets?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><p><code>Expanded</code> is just a shorthand for <code>Flexible</code></p><p>Using expanded this way:</p><pre><code><span class="token cMod">Expanded</span><span class="token cBase">(</span>
	child<span class="token cBase">:</span> <span class="token cMod">Foo</span><span class="token cBase">(</span><span class="token cBase">)</span><span class="token cBase">,</span>
<span class="token cBase">)</span><span class="token cBase">;</span></code></pre><p>is strictly equivalent to:</p><pre><code><span class="token cMod">Flexible</span><span class="token cBase">(</span>
	fit<span class="token cBase">:</span> FlexFit<span class="token cBase">.</span>tight<span class="token cBase">,</span>
	child<span class="token cBase">:</span> <span class="token cMod">Foo</span><span class="token cBase">(</span><span class="token cBase">)</span><span class="token cBase">,</span>
<span class="token cBase">)</span><span class="token cBase">;</span></code></pre><p>You may want to use <code>Flexible</code> over <code>Expanded</code> when you want a different <code>fit</code>, useful in some responsive layouts.</p><p>The difference between <code>FlexFit.tight</code> and <code>FlexFit.loose</code> is that loose will allow its child to have a maximum size while tight forces that child to fill all the available space.</p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://stackoverflow.com/questions/52645944/flutter-expanded-vs-flexible" rel="noreferrer" target="_blank" title="What is the difference between Expanded and Flexible widgets? Interview Questions Source To Answer">stackoverflow.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 4. What is the pubspec.yaml file and what does it do?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><ul><li>The <code>pubspec.yaml</code> file allows you to define the packages your app relies on, declare your assets like images, audio, video, etc. </li><li>It allows you to set constraints for your app. </li><li>For Android developers, this is roughly similar to a <code>build.gradle</code> file.</li></ul></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://medium.com/@dev.n/answering-questions-on-flutter-app-development-6d50eb7223f3" rel="noreferrer" target="_blank" title="What is the pubspec.yaml file and what does it do? Interview Questions Source To Answer">medium.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 5. Does Flutter work like a browser? How is it different from a WebView based application?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><p>To answer this question simply: <strong>Code you write for a WebView or an app that runs similarly has to go through multiple layers to finally get executed.</strong> In essence, Flutter leapfrogs that by <strong>compiling down to native ARM</strong> code to execute on both platforms. “Hybrid” apps are slow, sluggish and look different from the platform they run on. Flutter apps run much, much faster than their hybrid counterparts. Also, it’s much easier to access native components and sensors using plugins rather than using WebViews which can’t take full use of their platform.</p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://medium.com/@dev.n/answering-questions-on-flutter-app-development-6d50eb7223f3" rel="noreferrer" target="_blank" title="Does Flutter work like a browser? How is it different from a WebView based application? Interview Questions Source To Answer">medium.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 6. When should you use WidgetsBindingObserver?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><p>WidgetsBindingObserver should be used when we want to listen to the <code>AppLifecycleState</code> and call stop/start on our services.</p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://www.filledstacks.com/post/flutter-application-life-cycle-management/" rel="noreferrer" target="_blank" title="When should you use WidgetsBindingObserver? Interview Questions Source To Answer">www.filledstacks.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 7. What is the difference between "main()" and "runApp()" functions in Flutter?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><ul><li><code>main ()</code> function came from <em>Java</em>-like languages so it's where all program started, without it, you can't write any program on Flutter even without UI.</li><li><code>runApp()</code> function should return <em>Widget</em> that would be attached to the screen as a root of the <em>Widget Tree</em> that will be rendered.</li></ul></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://stackoverflow.com/questions/58883728/what-is-the-difference-between-main-function-and-the-runapp-function-in-flutte" rel="noreferrer" target="_blank" title="What is the difference between &quot;main()&quot; and &quot;runApp()&quot; functions in Flutter? Interview Questions Source To Answer">stackoverflow.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 8. What is an App state?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><ul><li>State that is not <em>ephemeral</em>, that you want to share across many parts of your app, and that you want to keep between user sessions, is what we call <strong>application state</strong> (sometimes also called <em>shared state</em>).</li><li>Examples of application state:
		-   User preferences
		-   Login info
		-   Notifications in a social networking app
		-   The shopping cart in an e-commerce app
		-   Read/unread state of articles in a news app</li></ul></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://flutter.dev/docs/development/data-and-backend/state-mgmt/ephemeral-vs-app" rel="noreferrer" target="_blank" title="What is an App state?  Interview Questions Source To Answer">flutter.dev</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 9. What is the pubspec.yaml file and what does it do?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><p>The <code>Pubspec.yaml</code> allows you to define the packages your app relies on, declare your assets like images, audio, video, etc. It also allows you to set constraints for your app. For Android developers, this is roughly similar to a <code>build.gradle</code> file, but the differences between the two are also evident.</p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://medium.com/@dev.n/answering-questions-on-flutter-app-development-6d50eb7223f3" rel="noreferrer" target="_blank" title="What is the pubspec.yaml file and what does it do? Interview Questions Source To Answer">medium.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 10. What are the different build modes in Flutter?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><ul><li>The Flutter tooling supports three modes when compiling your app, and a headless mode for testing. </li><li>You choose a compilation mode depending on where you are in the development cycle.</li><li>The modes are:
		- Debug
		- Profile
		- Release</li></ul></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://flutter.dev/docs/testing/build-modes" rel="noreferrer" target="_blank" title="What are the different build modes in Flutter? Interview Questions Source To Answer">flutter.dev</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 11. What is Dart and why does Flutter use it?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><p><strong>Dart</strong> is an <em>object-oriented</em>, <em>garbage-collected</em> programming language that you use to develop Flutter apps.
It was also created by Google, but is open-source, and has community inside and outside Google.
Dart was chosen as the language of <strong>Flutter</strong> for the following reason: </p><ul><li>Dart is <strong>AOT</strong> (Ahead Of Time) compiled to fast, predictable, native code, which allows almost all of Flutter to be written in Dart. This not only makes Flutter fast, virtually everything (including all the widgets) can be customized.</li><li>Dart can also be <strong>JIT</strong> (Just In Time) compiled for exceptionally fast development cycles and game-changing workflow (including Flutter’s popular sub-second stateful hot reload).</li><li>Dart allows Flutter to avoid the need for a separate declarative layout language like <em>JSX</em> or <em>XML</em>, or separate visual interface builders, because Dart’s declarative, programmatic layout is easy to read and visualize. And with all the layout in one language and in one place, it is easy for Flutter to provide advanced tooling that makes layout a snap.</li></ul></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://hackernoon.com/why-flutter-uses-dart-dd635a054ebf" rel="noreferrer" target="_blank" title="What is Dart and why does Flutter use it? Interview Questions Source To Answer">hackernoon.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 12. How many types of widgets are there in Flutter?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><p>There are two types of widgets:
1.  <strong>StatelessWidget</strong> : A widget that does not require mutable state.
2.  <strong>StatefulWidget</strong>: A widget that has mutable state.</p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://proandroiddev.com/flutter-from-zero-to-comfortable-6b1d6b2d20e" rel="noreferrer" target="_blank" title="How many types of widgets are there in Flutter? Interview Questions Source To Answer">proandroiddev.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 13. How is Flutter different from a WebView based application?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><ul><li>Code you write for a <strong>WebView</strong> or an app that runs similarly has to go through multiple layers to finally get executed (like Cordova for Ionic).<strong> In essence, Flutter leapfrogs that by </strong>compiling down to native <strong>ARM</strong> code to execute on both platforms. </li><li>“Hybrid” apps are slow, sluggish and look different from the platform they run on. <em>Flutter</em> apps run much, much faster than their hybrid counterparts. </li><li>It’s much easier to access native components and sensors using plugins rather than using <strong>WebView</strong> which can’t take full use of their platform.</li></ul></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://medium.com/@dev.n/answering-questions-on-flutter-app-development-6d50eb7223f3" rel="noreferrer" target="_blank" title="How is Flutter different from a WebView based application? Interview Questions Source To Answer">medium.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 14. What is a "widget" and mention its importance in Flutter?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><ul><li>Widgets are basically the UI components in Flutter.</li><li>It is a way to describe the configuration of an <em>Element</em>.</li><li>They are inspired from components in <strong>React</strong>.</li></ul><p>Widgets are important in Flutter because everything within a Flutter application is a  <strong>Widget</strong>  , from a simple “<em>Text”</em>  to “<em>Buttons”</em>  to “<em>Screen Layouts”</em>.</p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://stackoverflow.com/questions/50958238/what-is-a-widget-in-flutter" rel="noreferrer" target="_blank" title="What is a &quot;widget&quot; and mention its importance in Flutter? Interview Questions Source To Answer">stackoverflow.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 15. What is Fat Arrow Notation in Dart and when do you use it?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><p>The fat arrow syntax is simply a short hand for returning an expression and is similar to <code>(){ return expression; }</code>.</p><p>The fat arrow is for returning a single line, braces are for returning a code block.</p><p>Only an expression—not a statement—can appear between the arrow (<code>=&gt;</code>) and the semicolon (<code>;</code>). For example, you can’t put an <em>if</em> statement there, but you can use a <em>conditional</em> expression</p><pre><code><span class="token cComment">// Normal function</span>
<span class="token cVar">void</span> <span class="token cMod">function1</span><span class="token cBase">(</span>int a<span class="token cBase">)</span> <span class="token cBase">{</span>
  <span class="token cVar">if</span> <span class="token cBase">(</span>a <span class="token cBase">==</span> <span class="token cNum">3</span><span class="token cBase">)</span> <span class="token cBase">{</span>
    <span class="token cMod">print</span><span class="token cBase">(</span><span class="token cString">'arg was 3'</span><span class="token cBase">)</span><span class="token cBase">;</span>
  <span class="token cBase">}</span> <span class="token cVar">else</span> <span class="token cBase">{</span>
    <span class="token cMod">print</span><span class="token cBase">(</span><span class="token cString">'arg was not 3'</span><span class="token cBase">)</span><span class="token cBase">;</span>
  <span class="token cBase">}</span>
<span class="token cBase">}</span>

<span class="token cComment">// Arrow Function</span>
<span class="token cVar">void</span> <span class="token cMod">function2</span><span class="token cBase">(</span>int a<span class="token cBase">)</span> <span class="token cBase">=</span><span class="token cBase">&gt;</span> <span class="token cMod">print</span><span class="token cBase">(</span><span class="token cString">'arg was ${a == 3 ? '</span><span class="token cString">' : '</span>not <span class="token cString">'}3'</span><span class="token cBase">)</span><span class="token cBase">;</span></code></pre></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://stackoverflow.com/questions/51868395/flutter-dart-difference-between-and/51869508" rel="noreferrer" target="_blank" title="What is Fat Arrow Notation in Dart and when do you use it? Interview Questions Source To Answer">stackoverflow.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 16. Why do we pass functions to widgets?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 17. What is Streams in Flutter/Dart?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 18. What is release mode and when do you use it?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 19. Differentiate between named parameters and positional parameters in Dart?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 20. What is the difference between Scaffold and Container in Flutter?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 21. What is ScopedModel / BLoC Pattern?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 22. What are Null-aware operators?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 23. What is profile mode and when do you use it?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 24. What are packages and plugins in Flutter?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 25. Do you know what Ephemeral state means?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 26. Explain the different types of Streams?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 27. Explain Navigator Widget and its push pop functions in Flutter?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 28. How do you check if an async void method is completed in Dart?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 29. Where are the layout files? Why doesn’t Flutter have layout files?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 30. What are some pros of Flutter?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 31. Why is the build() method on State and not Stateful Widget?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 32. What are keys in Flutter and when to use it?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 33. Differentiate StatelessWidget and StatefulWidget?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 34. How is InheritedWidget different from Provider?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 35. Differentiate between required and optional parameters in Dart</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 36. Differentiate between Hot Restart and Hot Reload?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 37. What is debug mode and when do you use it?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 38. When do we use double.INFINITY?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 39. How to declare async function as a variable in Dart?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 40. How is whenCompleted() different from then() in Future?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 41. Name some cons of using Flutter?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 42. How would you execute code only in debug mode?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 43. How to duplicate repeating items inside a Dart list?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 44. How to get difference of lists in Flutter/Dart?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 45. What does "non-nullable by default" mean in Dart?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 46. What is the difference between React Native and Flutter in-depth?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 47. Explain async, await in Flutter/Dart?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 48. What is the difference between double.INFINITY and MediaQuery?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 49. What is Future in Flutter/Dart?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 50. What is the purpose of SafeArea in Flutter?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 51. What does a class with a method named ._() mean in Dart/Flutter?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 52. When would you use App state or Ephemeral state over another?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 53. What is a difference between these operators "?? and ?."</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 54. What is a MediaQuery in Flutter and when do we use it?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 55. Why is exit(0) not preferred for closing an app?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 56. What are Global Keys?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 57. How does Dart AOT work?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 58. What's the difference between async and async* in Dart?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 59. What are some pros and cons of Scoped Model vs BLoC and vice versa?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 60. What are the similarities and differences of Future and Stream?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 61. Why should you use kReleaseMode instead of assert?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 62. How to compare two dates that are constructed differently in Dart?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 63. How do you convert a List into a Map in Dart?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 64. Why Are StatefulWidget and State Separate Classes?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 65. What is the difference between debug mode and profile mode?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 66. Explain Stateful Widget Lifecycle in details</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 67. How is AnimationController different from Timer?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 68. List some approaches for State management in Flutter</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/flutter-interview-questions">all 68 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div></div>
