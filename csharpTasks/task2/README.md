# ������� �� .Net �2

� ���� ������� ��������� �������� ������� ��� ����� �����������.
��� ����� � ������� ���� ����������� ���������� ����������� (�����) 
��� �������� ���� ��� ����� ������������� ��������. 

������������� �������:
```
Factory factory = new Factory(); // ������� �����������
SomeProvider provider = new SomeProvider(options); // �������� ����������, 
    // ����� - ��������� ������������
factory.AddProvider(provider); // ���������� ���������� � �������
factory.CreateSomething(); // �������� ������� � ������� ����������
provider = factory.GetProvider<SomeProvider>(); // ����� ������ ����������
provider.CreateObject(); // �������� ������� ���� ����� ���������
```  

�� ��������, ��� � ��������� - ��� ���� ������, �.�
```
factory.AddProvider(new TruckProvider());
Car car = factory.CreateTruck(); // ����� ������ ��������
```
����, ����� ����� ��������� �������� �������, ����� ����������� ������ �������.
��� ������� ������� ������ ����� ������ ������, ��������� � ��������. 
���� ������������ �������� - ������ ������ � ���������� ����������: 
���-�� �����, �������, ������������ � �.�. ����� ����� ��������� ��� � Program.cs ��������.

## ���������:
- ������ ������ �� ������� ����������� �����, �������� �� �������� ��������� ��� ���� ��������� ����������
- ������ ����� ��� ����������� ���������� ���������, � ����� ���������� ��� �������� ����� �� ���� ����������.

## ���������� ����������
- ��� �� Program.cs ������ ����������
- ���������� �������� ������� ���� ������������ �������, ��� �� ������� ������� �������������
- ���� ��������� �� ����� ��
- ��� ������� �� ������-���������� �������.

������� �� ������������ ��������, �������������.