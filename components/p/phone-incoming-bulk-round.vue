<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l_aruko7w"/><path class="zvk288b7k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-incoming-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.l_aruko7w {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 2h1c2.253 0 4.118 1.603 4.928 3.629c.351.877.592 1.812.592 2.761c0 .419-.05.84-.177 1.24a2.65 2.65 0 0 1-.636 1.077a1.123 1.123 0 0 0 0 1.586l2 2a1.123 1.123 0 0 0 1.586 0c.459-.459 1.038-.777 1.651-.982A6.5 6.5 0 0 1 18 13h1c.53 0 1.023.211 1.424.551C21.61 14.555 22 16.522 22 18v1c0 .797-.314 1.558-.879 2.121A3 3 0 0 1 19 22a16.8 16.8 0 0 1-6.617-1.336a16.9 16.9 0 0 1-5.404-3.643a16.9 16.9 0 0 1-3.643-5.404A16.8 16.8 0 0 1 2 5c0-.797.314-1.558.879-2.121A3 3 0 0 1 5 2");
}

.zvk288b7k {
  d: path("M14 9V5a1 1 0 0 1 2 0v1.586l4.293-4.293a.999.999 0 1 1 1.414 1.414L17.414 8H19a1 1 0 0 1 0 2h-4a1 1 0 0 1-1-1");
}

</style>
