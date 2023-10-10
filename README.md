# Language-Parser
Formal Languages Coursework

//README
//This section is just a clarification of the parser. Given an input, the parser will
//base its analysis solely on the syntax, not the context.
//In the following example:   DEF P2P xXx { 3*Q()+R(6,Q(5))  };
//
//The parser will report that there is a missing space between the function name and
//the parameter name. At first thought, given the context we know that P2P is
//supposed to be the function name. However, the parser recognises a function name
//as a continuous sequence of UPPERCASE characters. Therefore, in terms of syntax,
//the function name is P and the parameter name is "technically" 2P. Hence there is
//a missing space between function name and parameter name.
