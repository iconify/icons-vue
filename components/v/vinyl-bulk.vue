<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fotd3mbrk"/><path class="jl-2kwbhh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:vinyl-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fotd3mbrk {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2.786 8.107C4.936 3.02 10.804.639 15.892 2.788s7.469 8.016 5.32 13.104s-8.016 7.469-13.104 5.32S.637 13.195 2.786 8.107M12 11a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

.jl-2kwbhh {
  d: path("M5.55 9.275a7 7 0 0 1 1.5-2.225a7 7 0 0 1 2.225-1.5A6.9 6.9 0 0 1 12 5a1 1 0 0 1 0 2a4.97 4.97 0 0 0-3.536 1.464A4.97 4.97 0 0 0 7 12a1 1 0 0 1-2 0a6.9 6.9 0 0 1 .55-2.725m12.9 5.45a7 7 0 0 1-1.5 2.225a7 7 0 0 1-2.225 1.5A6.9 6.9 0 0 1 12 19a1 1 0 0 1 0-2a4.97 4.97 0 0 0 3.536-1.464A4.97 4.97 0 0 0 17 12a1 1 0 0 1 2 0a6.9 6.9 0 0 1-.55 2.725");
}

</style>
