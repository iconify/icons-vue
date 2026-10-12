<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ghh_5mbcw"/><path class="sdqzc6qod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:monk-robe" /></template>
<style>
.ghh_5mbcw {
  d: path("M10.25 2.75h3.5q.75 0 1.41.35l3.43 1.8q.66.35.85 1.07l1.62 6.06q.19.72-.55.84l-1.52.26q-.74.12-.95-.6l-.08-.31q-.21-.72-.11.02l1.05 8.27q.1.74-.65.74H5.75q-.75 0-.65-.74l1.05-8.27q.1-.74-.11-.02l-.08.31q-.21.72-.95.6l-1.52-.26q-.74-.12-.55-.84l1.62-6.06q.19-.72.85-1.07l3.43-1.8q.66-.35 1.41-.35");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sdqzc6qod {
  d: path("m10 4.5l2 3l2-3m1.92 2.51l1.16.73q.42.26.1.64l-7.86 9.49q-.32.38-.78.18l-1.33-.6q-.46-.2-.14-.58l8.11-9.74q.32-.38.74-.12");
}

</style>
