\documentclass[12pt,a4paper]{article}

\usepackage{graphicx}
\usepackage{geometry}
\usepackage{setspace}
\usepackage{titlesec}
\usepackage{float}

\geometry{margin=1in}
\onehalfspacing

\title{AICT System of Event Management}
\author{Term Project -- MCT-107L \\ Group Code: 2025-MCT-164}
\date{}

\begin{document}

\maketitle
\thispagestyle{empty}
\newpage

%------------------ Abstract ------------------
\section*{Abstract}
This project presents an ICT-based Event Management System developed as part of the AICT (MCT-107L) course. 
The system aims to manage event and participant data efficiently using modern information and communication technologies. 
Google Sheets is used for dataset creation and analysis, where VLOOKUP and MATCH functions are applied to retrieve event details automatically. 
Additional tools such as GitHub, Canva, Overleaf, and Mendeley are integrated to ensure proper documentation, version control, and presentation.

\newpage

%------------------ Introduction ------------------
\section{Introduction}
Event management involves organizing and handling information related to events, participants, venues, and schedules. 
Traditional manual systems are often inefficient, time-consuming, and prone to errors. 
With the advancement of information and communication technologies, digital systems can significantly improve accuracy and efficiency.
This project demonstrates an ICT-based solution for managing event-related information in an academic environment.

%------------------ Problem Statement ------------------
\section{Problem Statement}
Manual handling of event and participant data creates several challenges, including data inconsistency, difficulty in searching records, and lack of automation.
There is a need for a centralized digital system that can manage event information and automatically retrieve relevant details for participants.
This project addresses these issues by developing an Event Management Information System using ICT tools.

%------------------ Proposed System ------------------
\section{Proposed System}
The proposed system is based on Google Sheets as a lightweight database for storing event and participant records.
Separate sheets are maintained for events and participants.
VLOOKUP and MATCH functions are used to dynamically fetch event information based on event IDs.
The overall system workflow is designed and visualized using Canva, while documentation and version control are managed using Overleaf and GitHub.

%------------------ Dataset Design ------------------
\section{Dataset Design}
The dataset consists of ten participant records, as required by the project allocation rules.
Each participant record includes registration ID, name, CNIC, phone number, email, event ID, registration date, and payment status.
A separate events table stores event ID, event name, venue, and other details.
Screenshots of the dataset and analysis are provided below.

\begin{figure}[H]
\centering
\includegraphics[width=0.9\textwidth]{participants.png}
\caption{Participants Dataset}
\end{figure}

\begin{figure}[H]
\centering
\includegraphics[width=0.9\textwidth]{event_details.png}
\caption{Event Details using VLOOKUP and MATCH}
\end{figure}

%------------------ System Diagram ------------------
\section{System Flow Diagram}
The system flow diagram illustrates the working of the AICT-based Event Management System.
It shows how the admin creates events, participants register for events, and data is analyzed using spreadsheet functions to produce meaningful output.

\begin{figure}[H]
\centering
\includegraphics[width=0.85\textwidth]{system_flow.png}
\caption{AICT System of Event Management}
\end{figure}

%------------------ Analysis and Results ------------------
\section{Analysis and Results}
VLOOKUP and MATCH functions are used together to retrieve event details such as event name and venue based on the event ID entered in the participant record.
This approach avoids hardcoding column numbers and improves flexibility.
The results show accurate and automatic retrieval of event information, demonstrating effective use of ICT tools.

%------------------ Tools and Technologies ------------------
\section{Tools and Technologies}
The following tools were used in this project:
\begin{itemize}
\item Google Sheets for dataset creation and analysis
\item GitHub for version control and repository management
\item Canva for system diagrams and presentation
\item Overleaf for LaTeX-based report writing
\item Mendeley for reference management
\end{itemize}

%------------------ Conclusion ------------------
\section{Conclusion}
The AICT-based Event Management System successfully demonstrates how ICT tools can be used to manage and analyze event-related data.
The use of Google Sheets with VLOOKUP and MATCH provides an efficient and automated solution.
This project fulfills the requirements of a Complex Engineering Activity and highlights the importance of ICT in modern information systems.

%------------------ References ------------------
\newpage
\section*{References}
References will be managed and inserted using Mendeley in APA or IEEE format.

\end{document}
