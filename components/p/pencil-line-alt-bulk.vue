<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="grdafbujy"/><path class="zo6txot3s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-line-alt-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.grdafbujy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 16c0-.265.105-.52.293-.707l11-11a2.414 2.414 0 0 1 3.414 0l2 2a2.414 2.414 0 0 1 0 3.414l-11 11A1 1 0 0 1 8 21H4a1 1 0 0 1-1-1Z");
}

.zo6txot3s {
  d: path("M8 21a1 1 0 0 1 0-2h12a1 1 0 0 1 0 2Z");
}

</style>
