<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ho1s1j52m"/><path class="bpw7-9whh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:printer-bulk" /></template>
<style>
.bpw7-9whh {
  d: path("M7.999 2H16a3 3 0 0 1 3 3v2a1 1 0 0 1-2 0V5c0-.268-.108-.525-.299-.713A.96.96 0 0 0 16 4H8a.997.997 0 0 0-1 1v2a1 1 0 0 1-2 0V5a3.004 3.004 0 0 1 2.999-3M14 10a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Zm-6 4h8a3.004 3.004 0 0 1 3 3v2a3.004 3.004 0 0 1-3 3H8a3.004 3.004 0 0 1-3-3v-2a3.004 3.004 0 0 1 3-3m-1 5a1 1 0 0 0 1 1h8a1 1 0 0 0 1-1v-2c0-.268-.108-.525-.299-.713A.96.96 0 0 0 16 16H8a.997.997 0 0 0-1 1Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ho1s1j52m {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 6a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3Zm-9 6h4a1 1 0 0 0 0-2h-4a1 1 0 0 0 0 2");
}

</style>
