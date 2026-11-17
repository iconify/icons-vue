<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zlkd-2bms"/><path class="mm-j3hb_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:oil-barrel-duocolor-round" /></template>
<style>
.mm-j3hb_r {
  d: path("M3 3h18M3 21h18M5 3v18M19 3v18M3 12h2m14 0h2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zlkd-2bms {
  stroke-opacity: 0.4;
  d: path("M12 8s-3.111 2.222-3.111 4.889a3.111 3.111 0 1 0 6.222 0C15.111 10.222 12 8 12 8");
}

</style>
