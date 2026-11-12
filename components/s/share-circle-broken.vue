<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p3-348ccq"/><path class="gszbesbvo"/><path class="jvpt20bzs"/><path class="hlz_d0lwp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:share-circle-broken" /></template>
<style>
.gszbesbvo {
  d: path("M5.5 15C7.15685 15 8.5 16.3431 8.5 18C8.5 19.6569 7.15685 21 5.5 21C3.84315 21 2.5 19.6569 2.5 18");
}

.hlz_d0lwp {
  d: path("M10 20.748C10.6392 20.9125 11.3094 21 12 21C12.6906 21 13.3608 20.9125 14 20.748M4 13C4 10.6106 5.04752 8.46589 6.70838 7M17.2916 7C18.9525 8.46589 20 10.6106 20 13");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jvpt20bzs {
  d: path("M18.5 21C16.8431 21 15.5 19.6569 15.5 18C15.5 16.3431 16.8431 15 18.5 15C20.1569 15 21.5 16.3431 21.5 18");
}

.p3-348ccq {
  d: path("M12 3C10.3431 3 9 4.34315 9 6C9 7.65685 10.3431 9 12 9C13.6569 9 15 7.65685 15 6");
}

</style>
