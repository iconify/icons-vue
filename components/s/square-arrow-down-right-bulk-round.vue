<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yqxcxg4xa"/><path class="rqcrlogdz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-down-right-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rqcrlogdz {
  d: path("M11 16a1 1 0 0 1 0-2h1.586L8.293 9.707a.999.999 0 1 1 1.414-1.414L14 12.586V11a1 1 0 0 1 2 0v4a1 1 0 0 1-1 1Z");
}

.yqxcxg4xa {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5Z");
}

</style>
