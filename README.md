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
\usepackage{hyphenat}
\usepackage{fontawesome}
\input{glyphtounicode}


%---------- FONT OPTIONS ----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
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
\addtolength{\topmargin}{-.5in}
\addtolength{\textheight}{1.0in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands

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
    \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}


\newcommand{\resumeEducationHeading}[6]{
  \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & #2 \\
      \textit{\small#3} & \textit{\small #4} \\
      \textit{\small#5} & \textit{\small #6} \\
    \end{tabular*}\vspace{-5pt}
}


\newcommand{\resumeProjectHeading}[2]{
    \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & #2 \\
    \end{tabular*}\vspace{-7pt}
}


\newcommand{\resumeOrganizationHeading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{0.97\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textit{\small #2} \\
      \textit{\small#3}
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.15in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%---------- HEADING ----------

\begin{center}
    \textbf{\Huge \scshape Muthoju Sahithi} \\ \vspace{3pt}
    \small
    \faMobile \hspace{.5pt} \href{tel:7569221164}{+91 7569221164}
    $|$
    \faAt \hspace{.5pt} \href{mailto:sahithimuthoju2002@gmail.com}{sahithimuthoju2002@gmail.com}
    $|$
    \faLinkedinSquare \hspace{.5pt} \href{https://in.linkedin.com/in/sahithi-muthoju-a80757249}{LinkedIn}
    $|$
    \faGithub \hspace{.5pt} \href{https://github.com/sahithi-22}{GitHub}
    $|$
    \faMapMarker \hspace{.5pt} \href{https://maps.app.goo.gl/PSSGYfeQaVcFm5Bf8}{Hyderabad, India}
\end{center}



%----------- EDUCATION -----------

\section{Education}
  \vspace{3pt}
  \resumeSubHeadingListStart
    
   \resumeSubheading{Guru Nanak Institute of Technology (GNIT)}{Hyderabad, India}{B.Tech. in Computer Science and Engineering; \textbf{CGPA: 7.72/10.00}}{2019 -- 2023}
   \vspace{2pt}
   \resumeSubheading{Narayana Junior College}{Hyderabad, India}{Intermediate (MPC): \textbf{GPA: 9.7/10.0}}{2017 -- 2019}
   \vspace{2pt}
   \resumeSubheading{Trinity High School}{Mancherial, India}{SSC: \textbf{GPA: 9.7/10.0}}{2016 -- 2017}
   \vspace{2pt}

  
  \resumeSubHeadingListEnd



\section{Projects}

\textbf{Real-Time Chat Application} 
\begin{itemize}
\item Developed a real-time chat application using React, Node.js, and Socket.io.
\item Enabled users to create chat rooms, join existing ones, and send real-time messages.
\item Implemented user authentication for secure access to chat rooms.
\end{itemize}

\textbf{ToDo App Backend} 
\begin{itemize}
\item Developed a robust backend for a Todo application using Node.js, Express, and MongoDB.
\item Implemented user authentication and authorization.
\item Created a REST API for seamless integration.
\end{itemize}



%----------- SKILLS -----------
\section{Skills}
\vspace{5pt}

\begin{itemize}
\item \textbf{Programming Languages}: C++, JavaScript
\item \textbf{Web Technologies}: HTML/CSS, ReactJS, NodeJS, ExpressJS
\item \textbf{Tools/Frameworks}: Git
\item \textbf{Databases}: MongoDB
\item \textbf{Other Skills}: Data Structures and Algorithms (DSA), Operating Systems (OS), Computer Networks (CN), Database Management Systems (DBMS), Object-Oriented Programming (OOPS)
\end{itemize}





%----------- RELEVANT COURSEWORK -----------



%----------- CERTIFICATIONS -----------
% \section{Certifications}
%   \vspace{5pt}
%   \begin{itemize}[leftmargin=*,itemsep=5pt,topsep=0pt]
%     \item \textbf{Google IT Automation with Python Professional Certificate} (Coursera)
%     \item \textbf{Python (Basic) Certificate} (Hackerrank)
%     \item \textbf{Problem Solving (Basic) Certificate} (Hackerrank)
%   \end{itemize}









%----------- REFERENCES -----------

% \section{References}
  % \resumeSubHeadingListStart
    
  % \resumeSubHeadingListEnd



%-------------------------------------------
\end{document}# Resume
