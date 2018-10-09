The 10 checks that i have picked is:<br>
LawOfDemeter, ControlStatementBraces, ShortVariable, UnusedFormalParameter, GodClass, UselessParentheses, ConfusingTernary, GuardLogStatement, AvoidLiteralsInIfCondition, AvoidDeeplyNestedIfStmts.<br><br>
I generated a PMD report based on all checks and then i looked through it to see what checks that i thought was important.<br><br>
I picked LawOfDemeter because low coupling is a good idea because the lower the coupling is the less you have to change for example when you change part of a class then you don't have to change all classes that use one or more of the methods in the class.<br><br>
I picked ControlStatementBraces because braces is important without them it is a good bit easier to get unnecessarily confused.<br><br>
I picked ShortVariable because longer names can get unnecessarily difficult to read, in a best case scenario you can get an idea about what a variable does in just a glance.<br><br>
I picked UnusedFormalParameter because adding parameters that you don't need to use is strange.<br><br>
I picked GodClass because small classes can easily be reused so the less a class does the better.<br><br>
I picked UselessParentheses because if you for example have 5-10 parentheses and 1 or more of them isn't used then it can cause unnecessary confusion.<br><br>
I picked ConfusingTernary because if you have an else that is called when the variable is true then that could cause unnecessary confussion.<br><br>
I picked GuardLogStatement because if you don't check if the log level is enabled before trying to use it then that could cause unnecessary errors.<br><br>
I picked AvoidLiteralsInIfCondition because it is better to give a value a descriptive name than just putting it in an if because if someone else need to take over for you then they don't necessarily know where the value comes from.<br><br>
I picked AvoidDeeplyNestedIfStmts because they can be unnecessarily difficult to read and it would be better to make a more specific if condition so that you don't need deeply nested if's.
