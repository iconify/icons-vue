<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w-wcr0x5l"/><path class="s0pcbcceb"/><path class="w9yyn-zir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:property-roi" /></template>
<style>
.s0pcbcceb {
  d: path("M7 21v-3.5q0-.098.01-.196q.009-.098.028-.194q.02-.097.048-.191q.029-.094.066-.184q.038-.091.084-.178q.046-.086.101-.168t.117-.158t.132-.145q.069-.07.145-.132t.158-.117t.168-.101t.178-.084q.09-.037.184-.066q.094-.028.191-.048q.096-.019.194-.028T9 15.5t.196.01q.098.009.194.028q.097.02.191.048q.094.029.184.066q.091.038.178.084q.086.046.168.101t.158.117t.145.132t.132.145t.117.158t.101.168q.046.087.084.178q.037.09.066.184q.028.094.048.191q.019.096.028.194t.01.196v3.043m3.25.707L17 18.5l1.75 1.75l2.75-2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w-wcr0x5l {
  d: path("M10.531 21H3V10.5L12 3l9 7.5v2.169");
}

.w9yyn-zir {
  d: path("M18.75 15.5h2.75v2.75");
}

</style>
