<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mslh1kbfo"/><path class="xcidkrbkb"/><path class="n47emwxwf"/><circle class="cm1occc5o"/><circle class="uyz1plbbg"/><path class="z2mkixmlh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:niconico" /></template>
<style>
.cm1occc5o {
  cx: 33.297px;
  cy: 22.42px;
  r: 1.859px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mslh1kbfo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.128 37.201V14.703c0-.93-.837-1.673-1.86-1.673H7.732c-1.022 0-1.86.744-1.86 1.673v22.498c0 .93.838 1.673 1.86 1.673H40.27c1.022 0 1.86-.743 1.86-1.673");
}

.n47emwxwf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 29.578l-3.254 3.625h6.508z");
}

.uyz1plbbg {
  cx: 14.611px;
  cy: 26.231px;
  r: 1.859px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xcidkrbkb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.874 34.412v-16.92c0-.65-.65-1.208-1.487-1.208H10.706c-.837 0-1.487.558-1.487 1.209v16.826c0 .65.65 1.209 1.487 1.209h26.68c.745.093 1.488-.465 1.488-1.116M32.832 5.5l-7.809 7.53h-2.046L15.168 5.5");
}

.z2mkixmlh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.608 38.874c-.558 2.139-1.673 3.626-3.068 3.626c-1.301 0-2.51-1.487-3.068-3.626m23.056 0c-.558 2.139-1.674 3.626-3.068 3.626c-1.302 0-2.51-1.487-3.068-3.626");
}

</style>
