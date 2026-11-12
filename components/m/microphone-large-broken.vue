<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ow44-uqiu"/><path class="fvun-abzf"/><path class="c_apmbcjm"/><path class="df2pzh_wy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:microphone-large-broken" /></template>
<style>
.c_apmbcjm {
  d: path("M10 9.5C10 9.5 10.4727 9 12 9C13.5273 9 14 9.5 14 9.5");
}

.df2pzh_wy {
  d: path("M21 11V13C21 16.5337 18.9634 19.5918 16 21.0645M3 11V13C3 17.9706 7.02944 22 12 22");
}

.fvun-abzf {
  d: path("M10 6.5C10 6.5 10.4727 6 12 6C13.5273 6 14 6.5 14 6.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ow44-uqiu {
  d: path("M18 8V13C18 16.3137 15.3137 19 12 19C8.68629 19 6 16.3137 6 13V8C6 4.68629 8.68629 2 12 2C13.777 2 15.3736 2.7725 16.4722 4");
}

</style>
