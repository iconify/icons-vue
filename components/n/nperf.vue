<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f8us19bzc"/><path class="uhqgh8hde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nperf" /></template>
<style>
.f8us19bzc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.254 7.527H16.862a7.41 7.41 0 0 0-7.426 7.427v19.45L5.5 30.469m6.246 10.004h19.392a7.41 7.41 0 0 0 7.426-7.427v-19.45l3.936 3.936");
}

.uhqgh8hde {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.905 31.58v-9.44c0-3.159-2.644-5.72-5.905-5.72s-5.905 2.561-5.905 5.72m0 9.44V16.42");
}

</style>
