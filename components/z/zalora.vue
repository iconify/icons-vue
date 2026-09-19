<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s9tl8kbgw"/><rect class="jc1oydeao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zalora" /></template>
<style>
.jc1oydeao {
  width: 39px;
  height: 31px;
  x: 4.5px;
  y: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.s9tl8kbgw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.977 21.163v5.677h2.839m7.777 0v-5.677h1.858a1.906 1.906 0 0 1 0 3.813h-1.858m1.859.001l1.859 1.862M8 21.163h3.761L8 26.84h3.761m5.334-1.899h-2.459m-.614 1.882l1.845-5.66l1.846 5.677m8.741-.003a1.88 1.88 0 0 1-1.88-1.88V23.04a1.88 1.88 0 1 1 3.76 0v1.916a1.88 1.88 0 0 1-1.88 1.88m12.929-1.895h-2.46m-.613 1.882l1.845-5.66L40 26.84");
}

</style>
