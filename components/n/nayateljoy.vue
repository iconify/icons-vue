<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vw7e61bvl"/><circle class="kmm-5b7gw"/><path class="ne3bchbml"/><path class="g3z9obbtl"/><path class="hy76z2b2c"/><path class="j-l-qrbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nayateljoy" /></template>
<style>
.g3z9obbtl {
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 6;
  d: path("M39.578 9.15c-9.578-2.588-19.02.257-22.695 7.483c0 0-4.655 7.12.4 16.629");
}

.hy76z2b2c {
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 6;
  d: path("M35.647 24.763a13.8 13.8 0 0 0-1.802-3.59s-4.328-7.28-14.608-7.88");
}

.j-l-qrbnp {
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 6;
  d: path("M29.822 44.702c5.622-6.018 7.89-13.708 5.825-19.94");
}

.kmm-5b7gw {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
}

.ne3bchbml {
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 6;
  d: path("M3.708 16.878C5.75 26.571 12.56 33.684 20.66 33.684c0 0 8.75.353 15.007-8.951");
}

.vw7e61bvl {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M22.032 29.341V18.203l5.566 5.569z");
}

</style>
