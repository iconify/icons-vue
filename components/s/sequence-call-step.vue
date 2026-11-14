<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlalgvjsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sequence-call-step" /></template>
<style>
.rlalgvjsi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.742 15.568q-.265.21-.585.321T14.5 16C8 15.5 3 10.5 2.5 4.5q0-.098.01-.196q.009-.098.028-.194q.02-.097.048-.191q.029-.094.066-.184q.038-.091.084-.178q.046-.086.101-.168t.117-.158t.132-.145t.145-.132t.158-.117t.168-.101q.087-.046.178-.084q.09-.037.184-.066q.094-.028.191-.048q.096-.019.194-.028T4.5 2.5H7l1.5 3.75l-1.75 1.5c.75 2 2.5 3.75 4.5 4.5l1.5-1.75L16.5 12v2q0 .503-.238.947m.238 6.803v-2h2v-2h2v-2H22");
}

</style>
