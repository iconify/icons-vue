<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qebz58hxe"/><path class="z9xw-db0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-menu-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qebz58hxe {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

.z9xw-db0m {
  d: path("M16 7a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm-8 4h8a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2");
}

</style>
