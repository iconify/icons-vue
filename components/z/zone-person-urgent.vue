<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsxe1ybsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:zone-person-urgent" /></template>
<style>
.dsxe1ybsj {
  fill: currentColor;
  d: path("M3 6V3.616q0-.691.463-1.154T4.615 2H7v1H4.616q-.231 0-.424.192T4 3.616V6zm4 14H4.616q-.691 0-1.153-.462T3 18.384V16h1v2.385q0 .23.192.423t.423.192H7zM20 6V3.616q0-.232-.192-.424T19.385 3H17V2h2.385q.69 0 1.152.463T21 3.616V6zm-7.701 1.701q-.491-.491-.491-1.201t.491-1.201t1.201-.491t1.201.491t.491 1.201t-.491 1.201q-.492.491-1.201.491t-1.201-.491m-2.883 8.684l1.038-5.331L7.5 12.273V15.5h-1v-3.892l3.989-1.662q.644-.26.95-.353T12 9.5q.39 0 .725.208t.552.561l1 1.6q.237.368.523.71t.654.625l-.525.852q-.464-.371-.89-.853t-.789-1.068l-.835 4.25zm5.2 4.615q-.287 0-.43-.26t-.003-.51l4-6.98q.151-.244.438-.275q.287-.03.446.256l4 7q.172.269 0 .519q-.17.25-.451.25zm4.273-.727Q19 20.162 19 20t-.111-.273t-.273-.111t-.274.111t-.111.273t.111.273t.274.112q.161 0 .273-.112m-.658-1.889H19v-3.768h-.77z");
}

</style>
