<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k9tvu0bar"/><path class="nh65yj6hh"/><path class="owji2u8vw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nuclear-medicine" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k9tvu0bar {
  d: path("M21.5 12c0 2.21-4.25 4-9.5 4s-9.5-1.79-9.5-4S6.75 8 12 8s9.5 1.79 9.5 4");
}

.nh65yj6hh {
  d: path("M16.75 20.25c-1.91 1.08-5.59-1.71-8.25-6.25C5.91 9.46 5.34 4.88 7.25 3.75C9.16 2.67 12.84 5.46 15.5 10c2.59 4.54 3.16 9.12 1.25 10.25");
}

.owji2u8vw {
  d: path("M7.25 20.25C5.34 19.12 5.91 14.54 8.5 10c2.66-4.54 6.34-7.33 8.25-6.25C18.66 4.88 18.09 9.46 15.5 14c-2.66 4.54-6.34 7.33-8.25 6.25M12 12h.01");
}

</style>
