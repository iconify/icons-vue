<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rfr-6881q"/><path class="g8zdikbna"/><path class="p6wya-5hz"/><path class="rl8688b4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tinybit" /></template>
<style>
.g8zdikbna {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 24.076L6.201 13.8L23.977 3.5l17.822 10.3z");
}

.p6wya-5hz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 44.5L6.201 34.224V13.8L24 24.076zm0-20.424l-4.603-2.658l4.597-2.663l4.609 2.663z");
}

.rfr-6881q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 44.5l17.799-10.276V13.8L24 24.076z");
}

.rl8688b4h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 29.358L19.397 26.7v-5.282L24 24.076zm0 0l4.603-2.658v-5.282L24 24.076z");
}

</style>
