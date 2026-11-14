<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cj5mxnddk"/><path class="g49bi7yqe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:utility-bills" /></template>
<style>
.cj5mxnddk {
  d: path("m14.725 21.41l-.225.09l-2.5-1l-2.5 1l-2.5-1l-2.5 1v-17q0-.098.01-.196q.009-.098.028-.194q.02-.097.048-.191q.029-.094.066-.184q.038-.091.084-.178q.046-.086.101-.168t.117-.158t.132-.145t.145-.132t.158-.117t.168-.101q.087-.046.178-.084q.09-.037.184-.066q.094-.028.191-.048q.096-.019.194-.028T6.5 2.5h11q.098 0 .196.01q.098.009.194.028q.097.02.191.048q.094.029.184.066q.091.038.178.084q.086.046.168.101t.158.117t.145.132t.132.145t.117.158t.101.168q.046.087.084.178q.037.09.066.184q.028.094.048.191q.019.096.028.194t.01.196v8.043M8 7h8m-8 3.5h8M8 14h3.5");
}

.g49bi7yqe {
  d: path("m17.982 15.209l-2.016 2.394a.698.698 0 0 0 .534 1.147a1.108 1.108 0 0 1 1.059 1.434l-.059.191a.324.324 0 0 0 .562.297l2.001-2.501A.721.721 0 0 0 19.5 17a1.08 1.08 0 0 1-1.026-1.423l.026-.077a.303.303 0 0 0-.518-.291");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
