<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ng4_fhbpd"/><path class="tigf8rbmt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:race-crash" /></template>
<style>
.ng4_fhbpd {
  d: path("M4.5 10.5h-2V8L5 7h4.5l2-2.5h3L16 7l5.5 1v2.5h-1.6m-11.4 0H15");
}

.tigf8rbmt {
  d: path("M4.5 10.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm14.466.367Q19 10.685 19 10.5q0-.098-.01-.196q-.009-.098-.028-.194q-.02-.097-.048-.191q-.029-.094-.066-.184q-.038-.091-.084-.178q-.046-.086-.101-.168t-.117-.158t-.132-.145t-.145-.132t-.158-.117t-.168-.101q-.087-.046-.178-.084q-.09-.037-.184-.066q-.094-.028-.191-.048q-.096-.019-.194-.028T17 8.5t-.196.01q-.098.009-.194.028q-.097.02-.191.048q-.094.029-.184.066q-.091.038-.178.084q-.086.046-.168.101t-.158.117t-.145.132q-.07.069-.132.145t-.117.158t-.101.168t-.084.178q-.037.09-.066.184q-.028.094-.048.191q-.019.096-.028.194T15 10.5t.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145t.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028t.196.01q.193 0 .383-.037M18.75 15l.75 1.75l1.75.25l-1 1.5l.5 1.75H19l-1.25 1.25l-.75-1.75l-1.75-.5l1-1.25l-.5-1.75h1.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
