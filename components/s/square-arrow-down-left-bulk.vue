<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qebz58hxe"/><path class="jbwtnsb_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-down-left-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jbwtnsb_n {
  d: path("M8 15v-4a1 1 0 0 1 2 0v1.586l4.293-4.293a.999.999 0 1 1 1.414 1.414L11.414 14H13a1 1 0 0 1 0 2H9a1 1 0 0 1-1-1");
}

.qebz58hxe {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>
