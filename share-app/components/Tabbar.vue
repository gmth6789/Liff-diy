<template>
	<div class="flex flex-wrap diygw-col-24 justify-around diygw-bottom tabbar-clz">
					<div class="flex flex-wrap diygw-col-0 flex-direction-column items-center">
						<span class="flex icon1 diygw-col-0 icon1-clz diy-icon-shop"></span>
						<div class="diygw-col-0">หน้าหลัก</div>
					</div>
					<div class="flex flex-wrap diygw-col-0 flex-direction-column items-center">
						<span class="flex icon2 diygw-col-0 icon2-clz diy-icon-star"></span>
						<div class="diygw-col-0">ภารกิจ</div>
					</div>
					<div class="flex flex-wrap diygw-col-0 flex-direction-column items-center">
						<span class="flex icon diygw-col-0 icon-clz diy-icon-message"></span>
						<div class="diygw-col-0 text16-clz">10</div>
						<div class="diygw-col-0">สมัคร</div>
					</div>
					<div class="flex flex-wrap diygw-col-0 flex-direction-column items-center">
						<span class="flex icon4 diygw-col-0 icon4-clz diy-icon-people"></span>
						<div class="diygw-col-0">ข้อมูล</div>
					</div>
				</div>
</template>

	<style>
		.image1-size {
			height: 180px !important;
			width: 100%;
		}
		.flex-clz {
			padding-top: 10px;
			border-bottom-left-radius: 6px;
			padding-left: 10px;
			padding-bottom: 10px;
			border-top-right-radius: 6px;
			margin-right: 10px;
			background-color: rgba(255, 255, 255, 0.73);
			margin-left: 10px;
			overflow: visible;
			width: calc(100% - 10px - 10px) !important;
			border-top-left-radius: 6px;
			margin-top: -50px;
			border-bottom-right-radius: 6px;
			margin-bottom: 5px;
			padding-right: 10px;
		}
		.avatar-clz {
			margin-left: 5px;
			margin-top: -30px;
			margin-bottom: 5px;
			margin-right: 5px;
		}
		.avatar-badge-0 {
			padding-left: 0px;
			padding-right: 0px;
			right: -6px;
			top: -2px;
		}
		.flex2-clz {
			padding-top: 5px;
			padding-left: 0px;
			padding-bottom: 5px;
			padding-right: 0px;
		}
		.text-clz {
			font-size: 18px !important;
		}
		.text1-clz {
			margin-left: 5px;
			margin-top: 0px;
			margin-bottom: 0px;
			margin-right: 5px;
		}
		.text2-clz {
			padding-top: 5px;
			padding-left: 0px;
			font-size: 14px !important;
			padding-bottom: 5px;
			padding-right: 0px;
		}
		.flex5-clz {
			padding-top: 10px;
			border-bottom-left-radius: 6px;
			padding-left: 10px;
			font-size: 14px !important;
			padding-bottom: 10px;
			border-top-right-radius: 6px;
			margin-right: 10px;
			background-color: #ffffff;
			margin-left: 10px;
			overflow: visible;
			width: calc(100% - 10px - 10px) !important;
			border-top-left-radius: 6px;
			margin-top: 10px;
			border-bottom-right-radius: 6px;
			margin-bottom: 5px;
			padding-right: 10px;
		}
		.flex6-clz {
			padding-top: 10px;
			padding-left: 0px;
			padding-bottom: 10px;
			padding-right: 0px;
		}
		.text5-clz {
			padding-top: 0px;
			padding-left: 10px;
			padding-bottom: 0px;
			padding-right: 0px;
		}
		.flex7-clz {
			padding-top: 10px;
			padding-left: 0px;
			padding-bottom: 10px;
			padding-right: 0px;
		}
		.text7-clz {
			padding-top: 0px;
			padding-left: 10px;
			padding-bottom: 0px;
			padding-right: 0px;
		}
		.flex9-clz {
			padding-top: 10px;
			padding-left: 0px;
			padding-bottom: 10px;
			padding-right: 0px;
		}
		.text9-clz {
			padding-top: 0px;
			padding-left: 10px;
			padding-bottom: 0px;
			padding-right: 0px;
		}
		.flex16-clz {
			padding-top: 10px;
			padding-left: 0px;
			padding-bottom: 10px;
			padding-right: 0px;
		}
		.text12-clz {
			padding-top: 0px;
			padding-left: 10px;
			padding-bottom: 0px;
			padding-right: 0px;
		}
		.flex18-clz {
			padding-top: 10px;
			padding-left: 0px;
			padding-bottom: 10px;
			padding-right: 0px;
		}
		.text14-clz {
			padding-top: 0px;
			padding-left: 10px;
			padding-bottom: 0px;
			padding-right: 0px;
		}
		.flex20-clz {
			padding-top: 10px;
			border-bottom-left-radius: 6px;
			padding-left: 10px;
			padding-bottom: 10px;
			border-top-right-radius: 6px;
			margin-right: 10px;
			background-color: #ffffff;
			margin-left: 10px;
			overflow: visible;
			width: calc(100% - 10px - 10px) !important;
			border-top-left-radius: 6px;
			margin-top: 10px;
			border-bottom-right-radius: 6px;
			margin-bottom: 5px;
			padding-right: 10px;
		}
		.text29-clz {
			padding-top: 10px;
			border-bottom-left-radius: 60px;
			padding-left: 50px;
			font-size: 15px !important;
			padding-bottom: 10px;
			border-top-right-radius: 60px;
			margin-right: 5px;
			background-color: #d6d6d6;
			margin-left: 5px;
			overflow: hidden;
			border-top-left-radius: 60px;
			margin-top: 5px;
			border-bottom-right-radius: 60px;
			margin-bottom: 5px;
			padding-right: 50px;
		}
		.tabbar-clz {
			padding-top: 2px;
			box-shadow: 0px 1px 4px 2px rgba(31, 31, 31, 0.16);
			overflow: visible;
			left: 0px;
			bottom: 0px;
			padding-left: 2px;
			padding-bottom: 2px;
			padding-right: 2px;
		}
		.icon1-clz {
			color: #767272;
		}
		.icon1 {
			font-size: 30px;
		}
		.icon2-clz {
			color: #767272;
		}
		.icon2 {
			font-size: 30px;
		}
		.icon-clz {
			color: #767272;
		}
		.icon {
			font-size: 30px;
		}
		.text16-clz {
			padding-top: 2px;
			border-bottom-left-radius: 60px;
			z-index: 1;
			color: #ffffff;
			padding-left: 3px;
			font-size: 10rpx !important;
			padding-bottom: 2px;
			border-top-right-radius: 60px;
			right: -5px;
			background-color: #ff0000;
			overflow: hidden;
			top: -5px;
			border-top-left-radius: 60px;
			border-bottom-right-radius: 60px;
			position: absolute;
			padding-right: 3px;
		}
		.icon4-clz {
			color: #767272;
		}
		.icon4 {
			font-size: 30px;
		}
		.container24325 {
			padding-left: 0px;
			padding-right: 0px;
		}
	</style>