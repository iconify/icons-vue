<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qebz58hxe"/><path class="chmvdccpm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:textarea-bulk" /></template>
<style>
.chmvdccpm {
  d: path("M16 5a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Zm-6 4a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Zm8.293 3.293a.999.999 0 1 1 1.414 1.414l-6 6a.999.999 0 1 1-1.414-1.414Zm0 5a.999.999 0 1 1 1.414 1.414l-1 1a.999.999 0 1 1-1.414-1.414Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.qebz58hxe {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>
