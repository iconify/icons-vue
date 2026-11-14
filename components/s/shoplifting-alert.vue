<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pe0c2kbhc"/><path class="tm0s24b4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shoplifting-alert" /></template>
<style>
.pe0c2kbhc {
  d: path("M15.174 14.848C13.846 14.467 13.004 13.5 12 13.5c-1.25 0-2.25 1.5-4.25 1.5c-2.25 0-4.25-1.25-4.25-3.5V8C7 6.5 17 6.5 20.5 8v3.5q0 .111-.006.219");
}

.tm0s24b4g {
  d: path("M5.75 10.75a2 1.25 0 1 0 4 0a2 1.25 0 1 0-4 0Zm11.771.965q.171-.088.307-.197t.231-.234q.094-.126.143-.261t.048-.273q0-.061-.01-.123q-.009-.061-.028-.121t-.048-.119t-.066-.115t-.084-.111t-.101-.105q-.055-.052-.117-.099t-.132-.091q-.069-.043-.145-.082t-.158-.073t-.168-.063t-.178-.053q-.09-.023-.184-.041t-.191-.03t-.194-.018t-.196-.006q-.098 0-.196.006t-.194.018q-.097.012-.191.03t-.184.041t-.178.053q-.086.029-.168.063t-.158.073t-.145.082q-.07.044-.132.091t-.117.099t-.101.105t-.084.111q-.037.056-.066.115q-.028.059-.048.119q-.019.06-.028.121q-.01.062-.01.123q0 .079.016.157q.016.079.047.155q.032.077.079.15q.046.074.108.143q.061.069.135.133q.075.063.162.121q.086.057.184.107t.205.092M3.5 9.5l-1.5 4m18.5-4l1.25 2.5M18 14.5V18m0 3h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
