<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q_26azylz"/><path class="q57l7sblh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sim-card-5g" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q_26azylz {
  d: path("M10.921 21.5H6.5q-.098 0-.196-.01q-.098-.009-.194-.028q-.097-.02-.191-.048q-.094-.029-.184-.066q-.091-.038-.178-.084q-.086-.046-.168-.101t-.158-.117t-.145-.132q-.07-.069-.132-.145t-.117-.158t-.101-.168t-.084-.178q-.037-.09-.066-.184q-.028-.094-.048-.191q-.019-.096-.028-.194T4.5 19.5v-15q0-.098.01-.196q.009-.098.028-.194q.02-.097.048-.191q.029-.094.066-.184q.038-.091.084-.178q.046-.086.101-.168t.117-.158t.132-.145t.145-.132t.158-.117t.168-.101q.087-.046.178-.084q.09-.037.184-.066q.094-.028.191-.048q.096-.019.194-.028T6.5 2.5H14L18.5 7v5.908");
}

.q57l7sblh {
  d: path("M10.125 6.5h1.25A2.625 2.625 0 0 1 14 9.125v1.25A2.625 2.625 0 0 1 11.375 13h-1.25A2.625 2.625 0 0 1 7.5 10.375v-1.25A2.625 2.625 0 0 1 10.125 6.5m6.625 9H14v2.75h1a1.625 1.625 0 0 1 0 3.25h-1.25m7.75-6h-1.75a1.5 1.5 0 0 0-1.5 1.5v3a1.5 1.5 0 0 0 1.5 1.5h1.75v-2.75H20");
}

</style>
