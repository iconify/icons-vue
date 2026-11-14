<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rpb_occ7x"/><path class="pamquncuc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:trumpet-mute" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pamquncuc {
  d: path("M7 17h10a2 2 0 0 1 2 2a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2a2 2 0 0 1 2-2m1.5-9h7");
}

.rpb_occ7x {
  d: path("M11.233 3h1.534a1.75 1.75 0 0 1 1.648 1.161l3.75 10.5A1.75 1.75 0 0 1 16.517 17H7.483a1.75 1.75 0 0 1-1.648-2.339l3.75-10.5A1.75 1.75 0 0 1 11.233 3");
}

</style>
