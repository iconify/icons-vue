<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="phq3z4cqu"/><path class="g2zoyccuh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sim-card-data" /></template>
<style>
.g2zoyccuh {
  d: path("M9.25 9.5h2.5a1.75 1.75 0 0 1 1.75 1.75v3A1.75 1.75 0 0 1 11.75 16h-2.5a1.75 1.75 0 0 1-1.75-1.75v-3A1.75 1.75 0 0 1 9.25 9.5m7 8l2.25-2.25l2.25 2.25m-2.25-2.25v6.5m-2.25-2.25l2.25 2.25l2.25-2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.phq3z4cqu {
  d: path("M14.292 21.5H6.5q-.098 0-.196-.01q-.098-.009-.194-.028q-.097-.02-.191-.048q-.094-.029-.184-.066q-.091-.038-.178-.084q-.086-.046-.168-.101t-.158-.117t-.145-.132q-.07-.069-.132-.145t-.117-.158t-.101-.168t-.084-.178q-.037-.09-.066-.184q-.028-.094-.048-.191q-.019-.096-.028-.194T4.5 19.5v-15q0-.098.01-.196q.009-.098.028-.194q.02-.097.048-.191q.029-.094.066-.184q.038-.091.084-.178q.046-.086.101-.168t.117-.158t.132-.145t.145-.132t.158-.117t.168-.101q.087-.046.178-.084q.09-.037.184-.066q.094-.028.191-.048q.096-.019.194-.028T6.5 2.5h7L18 7v5.536");
}

</style>
