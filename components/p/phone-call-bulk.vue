<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="msd50iyst"/><path class="z-6ep7b4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-call-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.msd50iyst {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 2h3c.601 0 1.205.111 1.746.382c.543.271 1.007.716 1.203 1.302l1 3c.366 1.101-.505 2.286-1.242 3.023l-1 1a.414.414 0 0 0 0 .586l3 3a.414.414 0 0 0 .586 0l1-1c.737-.737 1.922-1.608 3.023-1.242l3 1c.586.196 1.031.66 1.302 1.203c.271.541.382 1.145.382 1.746v3c0 .797-.314 1.558-.879 2.121A3 3 0 0 1 19 22a16.8 16.8 0 0 1-6.617-1.336a16.9 16.9 0 0 1-5.404-3.643a16.9 16.9 0 0 1-3.643-5.404A16.8 16.8 0 0 1 2 5c0-.797.314-1.558.879-2.121A3 3 0 0 1 5 2");
}

.z-6ep7b4i {
  d: path("M15 2c1.862 0 3.636.731 4.95 2.05a6.9 6.9 0 0 1 1.499 2.225c.366.862.554 1.789.551 2.725a1 1 0 0 1-2 0a4.9 4.9 0 0 0-.393-1.946a5 5 0 0 0-1.071-1.59A4.97 4.97 0 0 0 15 4a1 1 0 0 1 0-2m0 3c1.064 0 2.078.418 2.828 1.172A3.98 3.98 0 0 1 19 9a1 1 0 0 1-2 0c0-.533-.207-1.039-.586-1.414A1.98 1.98 0 0 0 15 7a1 1 0 0 1 0-2");
}

</style>
