<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbhenabce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:severity-major" /></template>
<style>
.xbhenabce {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.108 18.5H6.933q-.085 0-.17-.006q-.085-.005-.169-.016t-.168-.028q-.083-.016-.165-.038t-.163-.049t-.159-.059q-.079-.032-.155-.069q-.077-.038-.151-.08t-.144-.089q-.071-.046-.139-.098q-.068-.051-.132-.107q-.065-.055-.125-.115q-.061-.059-.118-.123q-.056-.063-.109-.13q-.052-.067-.1-.137t-.091-.144t-.082-.149t-.072-.154t-.062-.158t-.051-.162t-.041-.165t-.03-.167q-.013-.084-.02-.169t-.008-.17t.003-.17t.013-.169q.01-.085.025-.168q.015-.084.036-.166q.02-.083.046-.164t.056-.16q.031-.079.067-.156t.077-.152l4.132-7.535q.084-.152.186-.292q.103-.14.224-.265q.12-.125.256-.233t.284-.198q.149-.089.309-.158q.159-.069.326-.117q.167-.047.339-.072t.345-.027t.346.019t.341.064t.329.108t.312.151q.151.085.289.19q.139.105.262.227t.23.26t.193.287l3.013 5.189M11 9.25v3m0 3h.01M15.5 17l2.75-2.75L21 17m-5.5 4l2.75-2.75L21 21");
}

</style>
