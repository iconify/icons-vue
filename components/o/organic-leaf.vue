<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hwbq1wnoo"/><path class="xj9qdibis"/><path class="io72nworo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:organic-leaf" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hwbq1wnoo {
  d: path("m12.71 3.31l.63.5q.7.56 1.6.43l.79-.12q.9-.13 1.23.71l.29.75q.34.83 1.17 1.17l.75.29q.84.34.71 1.23l-.12.79q-.13.9.43 1.6l.5.63q.56.71 0 1.42l-.5.63q-.56.7-.43 1.6l.12.79q.13.9-.71 1.23l-.75.29q-.83.34-1.17 1.17l-.29.75q-.33.84-1.23.71l-.79-.12q-.9-.13-1.6.43l-.63.5q-.71.56-1.42 0l-.63-.5q-.7-.56-1.6-.43l-.79.12q-.89.13-1.23-.71l-.29-.75q-.34-.83-1.17-1.17l-.75-.29q-.84-.33-.71-1.23l.12-.79q.13-.9-.43-1.6l-.5-.63q-.56-.71 0-1.42l.5-.63q.56-.7.43-1.6l-.12-.79q-.13-.9.71-1.23l.75-.29q.83-.34 1.17-1.17l.29-.75q.33-.84 1.23-.71l.79.12q.9.13 1.6-.43l.63-.5q.71-.56 1.42 0");
}

.io72nworo {
  d: path("m9.4 11.65l1.75 1.75l2.75-3.25M8 16l-1.25 1.25");
}

.xj9qdibis {
  d: path("M8 16q8.37.12 8.25-8.25Q7.88 7.63 8 16");
}

</style>
