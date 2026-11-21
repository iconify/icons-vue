<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ny6chcbuw"/><path class="ndueijxid"/><path class="zu810ebvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ping-pong-broken" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ndueijxid {
  d: path("M7.02344 8.87256L12.9619 14.8111");
}

.ny6chcbuw {
  d: path("M9.83602 3.91478C9.99392 3.81828 10.1573 3.72868 10.3261 3.64638C12.5817 2.54628 15.2869 2.99898 17.0615 4.77348C18.836 6.54808 19.2887 9.25328 18.1886 11.5089C17.0885 13.7646 14.678 15.0733 12.1871 14.7675C10.409 14.3364 9.16172 14.6136 7.84502 15.9303L5.69692 18.0784C5.07322 18.7021 4.31092 18.6328 3.75662 18.0784C3.20222 17.5241 3.13292 16.7618 3.75662 16.1381L5.90472 13.99C7.22142 12.6733 7.49862 11.426 7.06752 9.64788C6.92802 8.51198 7.12432 7.39278 7.59312 6.40688");
}

.zu810ebvy {
  d: path("M20.6867 18.5488C20.6867 19.8743 19.6122 20.9488 18.2867 20.9488C16.9612 20.9488 15.8867 19.8743 15.8867 18.5488C15.8867 17.2233 16.9612 16.1488 18.2867 16.1488C19.6122 16.1488 20.6867 17.2233 20.6867 18.5488Z");
}

</style>
