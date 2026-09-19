<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rkelngbtw"/><path class="oxiwoqy_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:windscribevpn" /></template>
<style>
.oxiwoqy_q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.82 14.48V33.7h3.07a3.43 3.43 0 0 0 2.2-1h0L24 27.34l5.9 5.38h0a3.52 3.52 0 0 0 2.21 1h3.07V14.48");
}

.rkelngbtw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 44.5l-14.5-6l-6-14.5l6-14.5l14.5-6l14.5 6l6 14.5l-6 14.5Z");
}

</style>
