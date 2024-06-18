Select *
From IDPsql
Where Pos = 'DE' 
And Age < 26
And [Tackles TFL] > 10
Order by Sk desc

--

Select *
From IDPsql
Where Pos = 'DL' 
And Age < 26
And [Tackles Comb] > 50


--

Select *
From IDPsql
Where Pos = 'LB' 
And Age < 26
And [Tackles Comb] > 100
Order by Sk desc

--

Select *
From IDPsql
Where Pos = 'DB' 
And Age < 26
And [Tackles Comb] > 100
Order by [Def Interceptions Int] desc

--

Select *
From IDPsql
Where Age < 26
And [Tackles Comb] > 100
Order by [Def Interceptions Int] desc
