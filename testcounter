//htmlでjavascriptとCSS読み込んでなんかする
function countChange(num) {
	var cnt = parseInt(document.form1.cnt_txt.value);
	document.form1.cnt_txt.value = cnt + num;
	zeroCount();
	//左側のボタンから出力された数値と現在のカウンターの値を出して出力する。
	//ついでにzeroCount()に飛ぶ
}
function countReset(num) {
	document.form1.cnt_txt.value = num;
	zeroCount();
	//左側のリセット。初期ではとりあえず20を代入している。
}

function countChange_2(num) {
	var cnt = parseInt(document.form2.cnt_txt_2.value);
	document.form2.cnt_txt_2.value = cnt + num;
	zeroCount();
	//右側の増減
}

function countChange_3(num) {
	var cnt = parseInt(document.form3.cnt_txt_3.value);
	document.form3.cnt_txt_3.value = cnt + num;
	zeroCount();

}

function countChange_4(num) {
	var cnt = parseInt(document.form4.cnt_txt_4.value);
	document.form4.cnt_txt_4.value = cnt + num;
	zeroCount();

}

function countReset_2(num) {
	document.form2.cnt_txt_2.value = num;
	zeroCount();
	//右側のリセット
}

function countReset_3(num) {
	document.form3.cnt_txt_3.value = num;
	zeroCount();
	//右側のリセット
}

function countReset_4(num) {
	document.form4.cnt_txt_4.value = num;
	zeroCount();
	//右側のリセット
}

function countResetAll(num) {
	document.form1.cnt_txt.value = num;
	document.form2.cnt_txt_2.value = num;
	document.form3.cnt_txt_3.value = num;
	document.form4.cnt_txt_4.value = num;
	countReset_P_1(0);
	countReset_P_2(0);
	countReset_P_3(0);
	countReset_P_4(0);
	generalReset(0);
	goyfCount_O();
	zeroCount();
	//全部リセット

}

function zeroCount() {
	var redCount = parseInt(document.form1.cnt_txt.value);
	var blueCount = parseInt(document.form2.cnt_txt_2.value);
	var orangeCount = parseInt(document.form3.cnt_txt_3.value);
	var greenCount = parseInt(document.form4.cnt_txt_4.value);

	//それぞれのカウンターの値を取得するやつ。
	if (redCount < 1) {
		$(".countOut").css(
			"color", "red");
	} else {
		$(".countOut").css(
			"color", "");
	}

	if (blueCount < 1) {
		$(".countOut_2").css(
			"color", "red");
	} else {
		$(".countOut_2").css(
			"color", "");
	}

	if (orangeCount < 1) {
		$(".countOut_3").css(
			"color", "red");
	} else {
		$(".countOut_3").css(
			"color", "");
	}

	if (greenCount < 1) {
		$(".countOut_4").css(
			"color", "red");
	} else {
		$(".countOut_4").css(
			"color", "");
	}
	//フォームの値が1未満の時、文字色を赤く変更し、1以上ならばもとに戻す。
	//数字が変わる操作をしたらとりあえずこの関数に飛ばす。
}

function countChange_P_1(num) {
	var cnt = parseInt(document.form1.poison.value);
	document.form1.poison.value = cnt + num;
	zeroCount();
	//
}

function countReset_P_1(num) {
	document.form1.poison.value = num;
	zeroCount();
	//
}

function countChange_P_2(num) {
	var cnt = parseInt(document.form2.poison.value);
	document.form2.poison.value = cnt + num;
	zeroCount();
	//
}

function countReset_P_2(num) {
	document.form2.poison.value = num;
	zeroCount();
	//
}

function countChange_P_3(num) {
	var cnt = parseInt(document.form3.poison.value);
	document.form3.poison.value = cnt + num;
	zeroCount();
	//
}

function countReset_P_3(num) {
	document.form3.poison.value = num;
	zeroCount();
	//
}

function countChange_P_4(num) {
	var cnt = parseInt(document.form4.poison.value);
	document.form4.poison.value = cnt + num;
	zeroCount();
	//
}

function countReset_P_4(num) {
	document.form4.poison.value = num;
	zeroCount();
	//
}
//ここからgeneralcounter

function generalReset(num) {
	generalD_1_1(num);
	generalD_1_2(num);
	generalD_1_3(num);
	generalD_2_1(num);
	generalD_2_2(num);
	generalD_2_3(num);
	generalD_3_1(num);
	generalD_3_2(num);
	generalD_3_3(num);
	generalD_4_1(num);
	generalD_4_2(num);
	generalD_4_3(num);
	// generalcounter のリセット
}

function generalD_1_1(num) {
	if (num == 0) {
		document.form1.general_1.value = num;
		return;
	}
	var cnt = parseInt(document.form1.general_1.value);
	document.form1.general_1.value = cnt + num;
}

function generalD_1_2(num) {
	if (num == 0) {
		document.form1.general_2.value = num;
		return;
	}
	var cnt = parseInt(document.form1.general_2.value);
	document.form1.general_2.value = cnt + num;
}

function generalD_1_3(num) {
	if (num == 0) {
		document.form1.general_3.value = num;
		return;
	}
	var cnt = parseInt(document.form1.general_3.value);
	document.form1.general_3.value = cnt + num;
}

function generalD_2_1(num) {
	if (num == 0) {
		document.form2.general_1.value = num;
		return;
	}
	var cnt = parseInt(document.form2.general_1.value);
	document.form2.general_1.value = cnt + num;
}

function generalD_2_2(num) {
	if (num == 0) {
		document.form2.general_2.value = num;
		return;
	}
	var cnt = parseInt(document.form2.general_2.value);
	document.form2.general_2.value = cnt + num;
}

function generalD_2_3(num) {
	if (num == 0) {
		document.form2.general_3.value = num;
		return;
	}
	var cnt = parseInt(document.form2.general_3.value);
	document.form2.general_3.value = cnt + num;
}

function generalD_3_1(num) {
	if (num == 0) {
		document.form3.general_1.value = num;
		return;
	}
	var cnt = parseInt(document.form3.general_1.value);
	document.form3.general_1.value = cnt + num;
}

function generalD_3_2(num) {
	if (num == 0) {
		document.form3.general_2.value = num;
		return;
	}
	var cnt = parseInt(document.form3.general_2.value);
	document.form3.general_2.value = cnt + num;
}

function generalD_3_3(num) {
	if (num == 0) {
		document.form3.general_3.value = num;
		return;
	}
	var cnt = parseInt(document.form3.general_3.value);
	document.form3.general_3.value = cnt + num;
}

function generalD_4_1(num) {
	if (num == 0) {
		document.form4.general_1.value = num;
		return;
	}
	var cnt = parseInt(document.form4.general_1.value);
	document.form4.general_1.value = cnt + num;
}

function generalD_4_2(num) {
	if (num == 0) {
		document.form4.general_2.value = num;
		return;
	}
	var cnt = parseInt(document.form4.general_2.value);
	document.form4.general_2.value = cnt + num;
}

function generalD_4_3(num) {
	if (num == 0) {
		document.form4.general_3.value = num;
		return;
	}
	var cnt = parseInt(document.form4.general_3.value);
	document.form4.general_3.value = cnt + num;
}
//ここからgoyfCounter

var dColor = "rgb(221, 221, 221)";

function goyfCount() {
	var btnCount = 8;
	var goyfL = $(".goyfCountL").css("background-color");
	var goyfC = $(".goyfCountC").css("background-color");
	var goyfI = $(".goyfCountI").css("background-color");
	var goyfS = $(".goyfCountS").css("background-color");
	var goyfE = $(".goyfCountE").css("background-color");
	var goyfA = $(".goyfCountA").css("background-color");
	var goyfP = $(".goyfCountP").css("background-color");
	var goyfT = $(".goyfCountT").css("background-color");
	if (goyfL == dColor) {
		btnCount--;
	}
	if (goyfC == dColor) {
		btnCount--;
	}
	if (goyfI == dColor) {
		btnCount--;
	}
	if (goyfS == dColor) {
		btnCount--;
	}
	if (goyfE == dColor) {
		btnCount--;
	}
	if (goyfA == dColor) {
		btnCount--;
	}
	if (goyfP == dColor) {
		btnCount--;
	}
	if (goyfT == dColor) {
		btnCount--;
	}
	var goyfTaf = btnCount + 1;
	document.formG.cnt_goyf.value = btnCount + "/" + goyfTaf;
}

function goyfCount_L() {
	var goyfL = $(".goyfCountL").css("background-color");
	if (goyfL == dColor) {
		$(".goyfCountL").css("background-color", "gray")
		.css("color", "white");
	} else {
		$(".goyfCountL").css("background-color", "")
		.css("color", "");
	}
	goyfCount();
}

function goyfCount_C() {
	var goyfC = $(".goyfCountC").css("background-color");
	if (goyfC == dColor) {
		$(".goyfCountC").css("background-color", "gray")
		.css("color", "white");
	} else {
		$(".goyfCountC").css("background-color", "")
		.css("color", "");
	}
	goyfCount();
}

function goyfCount_I() {
	var goyfI = $(".goyfCountI").css("background-color");
	if (goyfI == dColor) {
		$(".goyfCountI").css("background-color", "gray")
		.css("color", "white");
	} else {
		$(".goyfCountI").css("background-color", "")
		.css("color", "");
	}
	goyfCount();
}

function goyfCount_S() {
	var goyfS = $(".goyfCountS").css("background-color");
	if (goyfS == dColor) {
		$(".goyfCountS").css("background-color", "gray")
		.css("color", "white");
	} else {
		$(".goyfCountS").css("background-color", "")
		.css("color", "");
	}
	goyfCount();
}

function goyfCount_E() {
	var goyfE = $(".goyfCountE").css("background-color");
	if (goyfE == dColor) {
		$(".goyfCountE").css("background-color", "gray")
		.css("color", "white");
	} else {
		$(".goyfCountE").css("background-color", "")
		.css("color", "");
	}
	goyfCount();
}

function goyfCount_A() {
	var goyfA = $(".goyfCountA").css("background-color");
	if (goyfA == dColor) {
		$(".goyfCountA").css("background-color", "gray")
		.css("color", "white");
	} else {
		$(".goyfCountA").css("background-color", "")
		.css("color", "");
	}
	goyfCount();
}

function goyfCount_P() {
	var goyfP = $(".goyfCountP").css("background-color");
	if (goyfP == dColor) {
		$(".goyfCountP").css("background-color", "gray")
		.css("color", "white");
	} else {
		$(".goyfCountP").css("background-color", "")
		.css("color", "");
	}
	goyfCount();
}

function goyfCount_T() {
	var goyfT = $(".goyfCountT").css("background-color");
	if (goyfT == dColor) {
		$(".goyfCountT").css("background-color", "gray")
		.css("color", "white");
	} else {
		$(".goyfCountT").css("background-color", "")
		.css("color", "");
	}
	goyfCount();
}

function goyfCount_O() {
	$(".goyfCountL").css("background-color", "")
	.css("color", "");
	$(".goyfCountC").css("background-color", "")
	.css("color", "");
	$(".goyfCountI").css("background-color", "")
	.css("color", "");
	$(".goyfCountS").css("background-color", "")
	.css("color", "");
	$(".goyfCountE").css("background-color", "")
	.css("color", "");
	$(".goyfCountA").css("background-color", "")
	.css("color", "");
	$(".goyfCountP").css("background-color", "")
	.css("color", "");
	$(".goyfCountT").css("background-color", "")
	.css("color", "");
	goyfCount();
}

//numcounterを4つまで増やす

function addOrange() {
	var addBtn = parseInt(document.addP.orangeP.value);
	if (addBtn == "0") {
		$(".numCounter_3").css("display", "block");
		document.addP.orangeP.value = "1";
	} else {
		$(".numCounter_3").css("display", "none");
		document.addP.orangeP.value = "0";
	}
}

function addGreen() {
	var addBtn = parseInt(document.addP.greenP.value);
	if (addBtn == "0") {
		$(".numCounter_4").css("display", "block");
		document.addP.greenP.value = "1";
	} else {
		$(".numCounter_4").css("display", "none");
		document.addP.greenP.value = "0";
	}
}

//generalcounterを増やす
function addGeneral() {
	var addBtn = parseInt(document.addG.general.value);
	if (addBtn == "0") {
		$(".numButton_G_1").css("display", "inline");
		$(".numButton_G_2").css("display", "inline");
		$(".numButton_G_3").css("display", "inline");
		$(".numButton_G_4").css("display", "inline");
		document.addG.general.value = "1";
	} else {
		$(".numButton_G_1").css("display", "none");
		$(".numButton_G_2").css("display", "none");
		$(".numButton_G_3").css("display", "none");
		$(".numButton_G_4").css("display", "none");
		document.addG.general.value = "0";
	}
}
