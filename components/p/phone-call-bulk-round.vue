<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l_aruko7w"/><path class="z-6ep7b4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-call-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.l_aruko7w {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 2h1c2.253 0 4.118 1.603 4.928 3.629c.351.877.592 1.812.592 2.761c0 .419-.05.84-.177 1.24a2.65 2.65 0 0 1-.636 1.077a1.123 1.123 0 0 0 0 1.586l2 2a1.123 1.123 0 0 0 1.586 0c.459-.459 1.038-.777 1.651-.982A6.5 6.5 0 0 1 18 13h1c.53 0 1.023.211 1.424.551C21.61 14.555 22 16.522 22 18v1c0 .797-.314 1.558-.879 2.121A3 3 0 0 1 19 22a16.8 16.8 0 0 1-6.617-1.336a16.9 16.9 0 0 1-5.404-3.643a16.9 16.9 0 0 1-3.643-5.404A16.8 16.8 0 0 1 2 5c0-.797.314-1.558.879-2.121A3 3 0 0 1 5 2");
}

.z-6ep7b4i {
  d: path("M15 2c1.862 0 3.636.731 4.95 2.05a6.9 6.9 0 0 1 1.499 2.225c.366.862.554 1.789.551 2.725a1 1 0 0 1-2 0a4.9 4.9 0 0 0-.393-1.946a5 5 0 0 0-1.071-1.59A4.97 4.97 0 0 0 15 4a1 1 0 0 1 0-2m0 3c1.064 0 2.078.418 2.828 1.172A3.98 3.98 0 0 1 19 9a1 1 0 0 1-2 0c0-.533-.207-1.039-.586-1.414A1.98 1.98 0 0 0 15 7a1 1 0 0 1 0-2");
}

</style>
