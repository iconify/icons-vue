<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pn5tqtb4p"/><path class="v3-k5hhjl"/><path class="af3t0nyrd"/><path class="z2-7z3bev"/><path class="ecz8exzik"/><path class="j2tm-9biu"/><path class="zj2p4py0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wi-fi-broken" /></template>
<style>
.af3t0nyrd {
  d: path("M5.33301 12.295C7.39361 10.0709 10.1707 9.09151 12.8624 9.35689");
}

.ecz8exzik {
  d: path("M2 8.69695C2.78921 7.8451 3.6485 7.11498 4.55783 6.50659");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j2tm-9biu {
  d: path("M8.53711 4.68847C13.2031 3.42167 18.3509 4.75782 22.0004 8.69694");
}

.pn5tqtb4p {
  d: path("M8.66699 15.893C9.2104 15.3065 9.85347 14.8931 10.5374 14.6528");
}

.v3-k5hhjl {
  d: path("M13.376 14.6233C14.0924 14.8584 14.7672 15.2817 15.3337 15.8932");
}

.z2-7z3bev {
  d: path("M16.6309 10.624C17.3596 11.0681 18.0452 11.625 18.6659 12.2949");
}

.zj2p4py0y {
  stroke-linejoin: round;
  d: path("M12.0176 19.4644H12.0177");
}

</style>
