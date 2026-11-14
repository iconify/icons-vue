<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qmeiyr_ni"/><path class="jcc75l2jx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tax-car" /></template>
<style>
.jcc75l2jx {
  d: path("M4.5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm11.007 1.728q.113-.066.216-.146t.195-.172t.172-.196q.079-.104.144-.217q.065-.114.115-.234t.083-.247q.034-.126.051-.256q.017-.129.017-.26q0-.098-.01-.196q-.009-.098-.028-.194q-.02-.097-.048-.191q-.029-.094-.066-.184q-.038-.091-.084-.178q-.046-.086-.101-.168t-.117-.158t-.132-.145t-.145-.132t-.158-.117t-.168-.101q-.087-.046-.178-.084q-.09-.037-.184-.066q-.094-.028-.191-.048q-.096-.019-.194-.028T14.5 10t-.196.01q-.098.009-.194.028q-.097.02-.191.048q-.094.029-.184.066q-.091.038-.178.084q-.086.046-.168.101t-.158.117t-.145.132t-.132.145t-.117.158t-.101.168q-.046.087-.084.178q-.037.09-.066.184q-.028.094-.048.191q-.019.096-.028.194T12.5 12q0 .148.022.294q.022.147.065.288q.043.142.106.276q.064.133.146.256q.083.123.182.233q.1.109.215.203q.114.093.241.169q.128.075.265.132M15.5 21.5l6-6m-5 1h.01m3.99 4h.01");
}

.qmeiyr_ni {
  d: path("M2.5 10V7.5l2.5-1L7.5 3H13l2.5 3.5l3 1V10Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
