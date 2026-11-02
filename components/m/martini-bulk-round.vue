<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mnxq4l1uo"/><path class="iv0w9bbpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:martini-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.iv0w9bbpt {
  d: path("M7 5h10a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2m1 17a1 1 0 0 1 0-2h3v-9a1 1 0 0 1 2 0v9h3a1 1 0 0 1 0 2Z");
}

.mnxq4l1uo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m11.293 11.707l-7-7a1.36 1.36 0 0 1-.382-1.186C4.072 2.572 5.102 2 6 2h12c.898 0 1.928.572 2.089 1.521a1.34 1.34 0 0 1-.382 1.186l-7 7a1 1 0 0 1-1.414 0");
}

</style>
