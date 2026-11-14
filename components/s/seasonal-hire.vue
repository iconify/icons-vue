<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvwn_dkuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:seasonal-hire" /></template>
<style>
.mvwn_dkuo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.915 10.239q.259-.276.462-.595q.203-.32.342-.671t.21-.723T16 7.5q0-.197-.019-.392q-.02-.196-.058-.388q-.038-.193-.095-.381t-.132-.37q-.076-.181-.168-.355q-.093-.173-.202-.336t-.234-.316q-.125-.151-.264-.29t-.29-.264t-.316-.234q-.163-.109-.336-.202q-.174-.092-.355-.168q-.182-.075-.37-.132t-.381-.095t-.388-.058T12 3.5t-.392.019q-.196.02-.388.058q-.193.038-.381.095t-.37.132q-.181.076-.355.168q-.173.093-.336.202t-.316.234q-.151.125-.29.264t-.264.29t-.234.316q-.109.163-.202.336q-.092.174-.168.355q-.075.182-.132.37t-.095.381t-.058.388T8 7.5t.019.392q.02.196.058.388q.038.193.095.381t.132.37q.076.181.168.355q.093.173.202.336t.234.316q.125.151.264.29t.29.264t.316.234q.163.109.336.202q.174.092.355.168q.182.075.37.132t.381.095t.388.058t.392.019q.681 0 1.324-.225M4 21c0-3.572 2.791-5.947 6.592-6.415M15.5 17.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2-4.5v1.25m0 6.5V22M13 17.5h1.25m6.5 0H22m-7.75-3.25l1 1m5.5-1l-1 1m-5.5 5.5l1-1m5.5 1l-1-1");
}

</style>
