�����������  ������� 		 
1.	������� �������� ��� �������� ������������������ ������ ��������: ����� �������� (���������), ������ (���������� ���  �� ������).
2.	�������� � ��������� ������������������ ������� � ��������� �� ������.
3.	������� �������, ����������� XML-������� ������� POST, ������� ������������ 2 ������� (��. ����). ���������� ����������� ������ � ��. ����� ������, ��� � �������� ����� ���������� ���������  ������������� ������������, � ����������� ������ �������� � ������� � ��������.
 ����������� ������ ������:
������:
<?xml version="1.0" encoding="utf-8"?>
<request>
 <request-type>new-agt</request-type>
 <login>1234567890</login> 
 <password>password</password> 
</request>

�����: 
<?xml version="1.0" encoding="utf-8"?>
<response>
 <result-code>0</result-code>
</response>

��� ��� ������:
 0  � ��� ������
 1  � ����� ����� ���  ���������������
 2 � �������� ������ ��������
 3 � ������ ������
 5 � ������ ������ ��������� �����

��������� �������:
������:
<?xml version="1.0" encoding="utf-8"?>
<request>
 <request-type>agt-bal</request-type>
 <login>1234567890</login> 
 <password>password</password> 
</request>

�����:

<?xml version="1.0" encoding="utf-8"?>
<response>
  <result-code>0</result-code>
  <bal>100.00</bal>
</response>

11 -����� � ������ ������� �� ���������
12 -���� ��� �������� ���������