<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6u0s94si"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:starry-sky" /></template>
<style>
.v6u0s94si {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.62 4.32l.93 2.05q.38.82 1.27.92l2.24.26q.9.1.23.7l-1.66 1.52q-.67.61-.49 1.49l.46 2.21q.18.88-.61.44l-1.96-1.12q-.78-.44-1.56 0l-1.96 1.12q-.79.44-.61-.44l.46-2.21q.18-.88-.49-1.49L4.21 8.25q-.67-.6.23-.7l2.24-.26q.89-.1 1.27-.92l.93-2.05q.37-.82.74 0m8.78 6.5l.49 1.02q.15.32.5.36l1.13.15q.35.05.09.29l-.82.79q-.26.24-.19.58l.2 1.12q.07.34-.24.18l-1-.54q-.31-.17-.62 0l-1 .54q-.31.16-.24-.18l.2-1.12q.07-.34-.19-.58l-.82-.79q-.26-.24.09-.29l1.13-.15q.35-.04.5-.36l.49-1.02q.15-.32.3 0m-.9-7.32q.24 1.76 2 2q-1.76.24-2 2q-.24-1.76-2-2q1.76-.24 2-2M2.75 21.25c3-2.25 5.75-3.25 9-3.25s6.5 1 9.5 3.25");
}

</style>
