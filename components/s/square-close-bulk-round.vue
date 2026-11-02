<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yqxcxg4xa"/><path class="uloqrgb0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-close-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.uloqrgb0d {
  d: path("M9.707 8.293L12 10.586l2.293-2.293a.999.999 0 1 1 1.414 1.414L13.414 12l2.293 2.293a.999.999 0 1 1-1.414 1.414L12 13.414l-2.293 2.293a.999.999 0 1 1-1.414-1.414L10.586 12L8.293 9.707a.999.999 0 1 1 1.414-1.414");
}

.yqxcxg4xa {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5Z");
}

</style>
