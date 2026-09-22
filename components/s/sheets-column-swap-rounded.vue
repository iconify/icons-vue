<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfopdpbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sheets-column-swap-rounded" /></template>
<style>
.wfopdpbvt {
  fill: currentColor;
  d: path("M5.808 9.135q-.343 0-.576-.232Q5 8.67 5 8.327v-3.52q0-.342.232-.575T5.808 4h4.788q.343 0 .576.232q.232.233.232.576v3.519q0 .343-.232.576q-.233.232-.576.232zm.192-1h4.404V5H6zM13.385 20q-.344 0-.576-.232q-.232-.233-.232-.576v-7.269q0-.343.232-.575t.576-.232h4.807q.344 0 .576.232t.232.575v7.27q0 .343-.232.575t-.576.232zm.192-1H18v-2.942h-4.423zm0-3.942H18v-2.942h-4.423zm3.71-6.904l-2.471-2.529q-.141-.14-.15-.332q-.01-.191.145-.356q.17-.166.361-.166t.357.166L18 7.447v-2.1q0-.205.144-.343t.357-.138t.356.143t.143.357v2.98q0 .344-.232.576q-.233.232-.576.232H15.25q-.213 0-.356-.144q-.144-.144-.144-.357t.144-.356t.356-.143zM6 13.829v2.075q0 .212-.144.356t-.357.144t-.356-.144T5 15.904v-2.981q0-.343.232-.575q.232-.233.576-.233H8.75q.213 0 .356.144q.144.144.144.357t-.144.356t-.356.144H6.708l2.476 2.515q.147.146.154.344t-.16.368q-.164.155-.353.158t-.354-.162z");
}

</style>
