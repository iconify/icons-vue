<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="in0kqd9jy"/><path class="t88802bnu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:marigold-flower" /></template>
<style>
.in0kqd9jy {
  d: path("m12 2.5l1.224 1.638l1.813-.945l.392 2.007l2.044-.064l-.518 1.978l1.869.828L17.5 9.5l1.324 1.558l-1.869.828l.518 1.978l-2.044-.064l-.392 2.007l-1.813-.945L12 16.5l-1.224-1.638l-1.813.945l-.392-2.007l-2.044.064l.518-1.978l-1.869-.828L6.5 9.5L5.176 7.942l1.869-.828l-.518-1.978l2.044.064l.392-2.007l1.813.945Zm0 14v5");
}

.t88802bnu {
  d: path("M9.5 9.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM12 20c-3 0-4.5-1.5-4.5-3.5c2.5 0 4 1.25 4.5 3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
