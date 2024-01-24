## Temporal File: Latex for UWB (simple instruction)
### Structure and Text
Remember to use `\noindent` before your section or subsection, if you found the space in the beginning of your paragraph, like:  
- *I like it* (the format we prefer);
- &ensp;*I like it*(with two space before the sentence, we do not prefer it).    

If you want to change a line, use `\\` instead of just inputing `Enter` in your keyboard.  
Some symbols like `&` or `%` should use `\&` and `\%`, as they present their special functions in Latex.  
Use `\section{}` and `\subsection{}` and `\subsubsection{}` to make the title.  
Use `\textit{}` to show this *format* and `\textbf{}` to show this **format**.  
Use:  
> \begin{itemize}  
> \item a    
> \item b  
> \item c  
> \end{itemize}  


To show the effect like:  
> - a  
> - b  
> - c  


And use:  
> \begin{enumerate}  
> \item a  
> \item b  
> \end{enumerate}  


To show the effect like:  
> 1. a  
> 2. b  

### Graph
For graph inserted between lines, we can use:  
> \begin{figure}[H]  
> \centering  
> \includegraphics[width=1\textwidth]{images/std.jpg}   
> \caption{The standard deviation model. Please view the raw image in the Appendix section.}  
> \end{figure}  

You should revise `\includegraphics` for the image path in the latex system, and configure `width` to control its size. Also, you need to add captions by `\caption`.  

For big graphs inserted to one full page, use this: 
> \includeFullPageGraphics{images/std.jpg}  
