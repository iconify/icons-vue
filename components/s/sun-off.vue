<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cuiqvf5xq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sun-off" /></template>
<style>
.cuiqvf5xq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.001 11.915L8 12q0 .197.019.392q.02.196.058.388q.038.193.095.381t.132.37q.076.181.168.355q.093.173.202.336t.234.316q.125.151.264.29t.29.264t.316.234q.163.109.336.202q.174.092.355.168q.182.075.37.132t.381.095t.388.058T12 16l.071-.001M16 12.042V12q0-.197-.019-.392q-.02-.196-.058-.388q-.038-.193-.095-.381t-.132-.37q-.076-.181-.168-.355q-.093-.173-.202-.336t-.234-.316q-.125-.151-.264-.29t-.29-.264t-.316-.234q-.163-.109-.336-.202q-.174-.092-.355-.168q-.182-.075-.37-.132t-.381-.095t-.388-.058T12 8h-.029M12 2.5V5m0 14v2.5M2.5 12H5m14 0h2.5m-18-8.5l17 17");
}

</style>
