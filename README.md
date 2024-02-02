The latex code:-
%-------------------------
% Resume in Latex
% Author : Matty
% Based on: https://github.com/jakegut/resume (which was itself based on https://github.com/sb2nov/resume)
% License : MIT
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{xcolor}
\usepackage{fontawesome5}

\input{glyphtounicode}

% -------------------- FONT OPTIONS --------------------
% sans-serif
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% serif
% \usepackage{charter}

\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.5in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1in}
\addtolength{\topmargin}{-1in} % Default was -.5in
\addtolength{\textheight}{1.0in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Section formatting
\titleformat{\section}{
  \vspace{-5pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Subsection formatting
\titleformat{\subsection}{
  \vspace{-4pt}\scshape\raggedright\large
}{\hspace{-.15in}}{0em}{}[\color{black}\vspace{-8pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

% -------------------- CUSTOM COMMANDS --------------------
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & #2 \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}
\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\setlength{\footskip}{4.08003pt}

% -------------------- START OF DOCUMENT --------------------
\begin{document}

% -------------------- HEADING--------------------
\begin{flushright}
  % \vspace{-4pt}
  \color{gray}
  \item

\end{flushright}

\vspace{-23pt}

\begin{center}
    \textbf{\Huge \scshape Rahul Singh} \\ \vspace{1pt}
     \textbf{ \Large\scshape Army Institute of Technology,Pune
} \\ \vspace{4pt}
    \small 
    \faIcon{github}
    \href{https://github.com/rahulsingh5926}{\underline{github.com/rahulsingh5926 }} $  $
    \faIcon{code}
    \href{https://leetcode.com/rayash10/}
    {\underline{leetcode.com/rayash10}} $  $
    \faIcon{linkedin}
    \href{https://www.linkedin.com/in/rahul-singh-677486225/}{\underline{linkedin.com/in/rahul-singh-677486225}} $  $\\ \vspace{8pt}
    \faIcon{envelope}
    \href{mailto:rahulyash960@gmail.com}
    {\underline{rahulyash960@gmail.com}}
\end{center}

% -------------------- EDUCATION --------------------
\section{Education}
  \resumeSubHeadingListStart
  
    \resumeSubheading
      {Army Institute of Technology}{June 2025}
      {B.E. in Electronic and Telecommunication }{Current SGPA: 8.4/10}
      
    \resumeSubheading
      {Army Public School,Bathinda Cantt }{March 2021}
      {12Th standard}{ 91\%}

   

 

  \resumeSubHeadingListEnd

% -------------------- SKILLS --------------------
\section{Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
    
     \textbf{Languages}{:C, C++, Python, JavaScript, HTML, CSS.
 } \\
     
     \textbf{Tools}{: Git/GitHub, GitHub, Jupyter Notebook, VS Code, PyCharm.}\\
     
     \textbf{Frameworks}{: React, Bootstrap, Tailwind CSS.
} \\
    \textbf{Familiar}{: SQL, Android.} \\
    \textbf{Soft-skills}{: Calm Under Pressure, Problem-Solving, Helpful, Innovative.}
 
     
    }}
 \end{itemize}


% -------------------- EXPERIENCE --------------------
  \section{Experience}
  \resumeSubHeadingListStart

          \resumeProjectHeading
          {\textbf{CEAR Club} $|$ \footnotesize\emph{Member}\hspace{8pt}}{Sept. 2023 -- Present}\resumeItemListStart
           {\resumeItem{Involved in the club centered around robotics, IOT and building bots}}
           {\resumeItem{Successfully organized robotics event in Solutions.}}
\resumeItemListEnd
          \resumeProjectHeading{\textbf{Jaljivika Aerator Pump Automation} $|$ \footnotesize\emph{Group Project}\hspace{8pt}}{ Aug. 2023 - Dec. 2023}
\resumeItemListStart
    \resumeItem{Led IoT development for Bombay Sapphire's aerial pump automation, improving operational efficiency.}
    \resumeItem{Implemented an IoT platform to remotely monitor and control aerial pumps, reducing manual intervention by 60\%}
    \resumeItem{Designed a user-friendly interface for precise pump scheduling and automation.}
    \resumeItem{Established a robust system for logging pump usage and facilitating maintenance.}
\resumeItemListEnd

% -------------------- PROJECTS --------------------
\section{Projects}
    \vspace{-10pt} 
    \resumeProjectHeading
    {\textbf{ \href{https://github.com/rahulsingh5926/REACT-newsHUNT}{News Hunt \faLink}} $|$ \footnotesize\emph{JavaScript, News API, Git, HTML/CSS, React, VS Code }}{Sept. 2023}

    \resumeItemListStart
    \resumeItem{Developed dynamic web app for real-time news updates using React and News API.}
    \resumeItem{Utilized APIs to fetch news across diverse categories for a seamless user experience, leading to a remarkable 30\% increase in user engagement.}
    \resumeItemListEnd
    
    \resumeProjectHeading
    {\textbf {\href{https://github.com/rahulsingh5926/Health-Fitness}{Health \& Fitness Website \faLink}} $|$ \footnotesize\emph{JavaScript, ExerciseDB/Edamam APIs, HTML/CSS, Git, Tailwind CSS, VS Code }}{Dec. 2023}
    \resumeItemListStart
    \resumeItem{Designed a Health & Fitness website with BMI calculation, nutrition analysis, and interactive fitness exercises, contributing to a 33\% improvement in overall well-being across all age groups.}
    \resumeItemListEnd
    
    \resumeProjectHeading
    {\textbf{\href{https://your-news-hunt-link.com}{Shortest Path Finder \faLink}} $|$ \footnotesize\emph{JavaScript, Git, HTML/CSS }}{Jan. 2024}
    \resumeItemListStart
    \resumeItem{Developed project using Dijkstra's algorithm for finding the shortest path between nodes.}
    \resumeItem{Developed a user-friendly interface enabling seamless input of source-destination nodes, resulting in optimal paths and facilitating a 20\% faster journey to the destination.}
    \resumeItemListEnd
    
    \resumeSubHeadingListEnd
% ACHIEVEMENTS
\section{ACHIEVEMENTS}
\begin{itemize}[leftmargin=0.15in, label={}, itemsep=-2pt]
    \item \textbf{The New Indian Readers Merit Scholarship} (1st year).
    \item \textbf{ESSA Scholarship} (1st and 2nd Year).
    \item \textbf{Fourth Position} in WarTech Robotic Event.
    \item \textbf{Secured 1st Position (ZONAL LEVEL)} in Meshmerize Event (TechFest) organized by IIT Bombay.
\end{itemize}
\section{CO-CURRICULAR and INTERESTS}
\resumeItemListStart
\resumeItem{Active participation in diverse events including sports, robotics, and technical competitions.}
\resumeItem{Passionate about Badminton and table tennis}


\end{document}
