<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cirgusbhj"/><path class="ntc2gpbtp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:power-restart" /></template>
<style>
.cirgusbhj {
  d: path("M17.142 6.872a8 8 0 1 1-10.284 0");
}

.ntc2gpbtp {
  d: path("M3.75 6.75h3v3M12 3v8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
