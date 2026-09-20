<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="o6y2-j0ng"/><path class="dm70-bcsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:pill-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dm70-bcsa {
  d: path("M216.43 39.6a53.27 53.27 0 0 0-75.33 0L39.6 141.09a53.26 53.26 0 0 0 75.32 75.31l101.51-101.49a53.32 53.32 0 0 0 0-75.31M103.61 205.09a37.26 37.26 0 0 1-52.7-52.69L96 107.31L148.7 160Zm101.5-101.49L160 148.69L107.32 96l45.1-45.09a37.26 37.26 0 0 1 52.69 52.69m-15.43-21.26a8 8 0 0 1 0 11.32l-24 24a8 8 0 1 1-11.31-11.32l24-24a8 8 0 0 1 11.31 0");
}

.o6y2-j0ng {
  d: path("m160 160l-50.75 50.75a45.26 45.26 0 0 1-64 0a45.26 45.26 0 0 1 0-64L96 96Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
