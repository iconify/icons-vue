<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xnpoe3g7v"/><path class="nbiuz816b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sd-card-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nbiuz816b {
  d: path("M11 10a1 1 0 0 1-2 0V7a1 1 0 0 1 2 0Zm3 0a1 1 0 0 1-2 0V7a1 1 0 0 1 2 0Zm3 0a1 1 0 0 1-2 0V7a1 1 0 0 1 2 0Z");
}

.xnpoe3g7v {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 7v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5V8c0-1.039.578-1.992 1.293-2.707l2-2C8.008 2.578 8.961 2 10 2h5a5 5 0 0 1 5 5");
}

</style>
