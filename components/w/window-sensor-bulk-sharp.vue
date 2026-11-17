<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qwb855b4i"/><path class="vz6txobay"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-sensor-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qwb855b4i {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 21V11a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1m2-6h3v-3H4Zm5 0h3v-3H9Zm-2 2H4v3h3Zm2 0v3h3v-3Z");
}

.vz6txobay {
  d: path("M20 11a6.99 6.99 0 0 0-7-7a1 1 0 1 1 0-2a9 9 0 0 1 9 9a1 1 0 0 1-2 0m-4 0a3 3 0 0 0-3-3a1.002 1.002 0 0 1-.866-1.5c.179-.309.509-.5.866-.5c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 18 11a1 1 0 0 1-2 0");
}

</style>
