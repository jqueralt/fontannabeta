%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     document d'exemple per observar               %
%     les característiques de XeLaTeX               %
%     amb la potència de KOMA-Script                %
%     i de scrpage2                                 %
%     autor: (C)2011 Joan Queralt Gil               %
%     llicència CC 2.0 by nc sa                     %
%     jqueralt a gmail.com                          %
%     cataLaTeX                                     %
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\documentclass[a4paper,%        % mida del paper
	      twoside,%         % impressió per les dues cares: hi ha pàgina dreta (senar) i esquerra (parell)
	      %twocolumn,%      % 2 columnes a partir del títol, inclou per tant el Resum i l'índex
	      11pt,%            % mida de la lletra
	      BCOR1.0cm,%       % coeficient pel marge d'enquadernació= 1 cm
	      DIV11,%           % relació àrea text escrit/pàgina; més text: DIV12,
	      abstracton,%      % article amb Resum (=Abstract)
	      ]{scrartcl}

\usepackage{amsmath}		% paquet de llenguatge matemàtic. Carregueu-lo abans de res.

%%%%%%%%%%%%%%%%%%%%%%%%%% XeLaTeX
\usepackage{lipsum}

\usepackage{fontspec}           % paquet per incorporar els tipus de lletra
\usepackage{xltxtra}		% paquet amb funcionalitats extres
\usepackage[catalan]{babel}

\setmainfont{Anna Beta}
% http://www.annavives.com/?page_id=624
\begin{document}
 \title{Prova del tipus de lletra Anna Beta}
 \author{Joan Queralt Gil}
 \date{\today}
 \maketitle
 \lipsum[1-3]
 
\end{document}
