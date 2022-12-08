package test1;

import java.util.Scanner;

public class khenthuong {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
Scanner sc = new Scanner(System.in);
System.out.println("nhap vao diem trung binh cua ban: ");
double diemtb = sc.nextDouble();
int ketqua;
ketqua = diemtb >= 5 ? 500:0;
System.out.println("ket qua cua ban la"+ketqua);
	}

}
