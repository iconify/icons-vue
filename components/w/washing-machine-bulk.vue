<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nrnkr7bfl"/><path class="ya5qky4nj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:washing-machine-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nrnkr7bfl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 5a3 3 0 0 1 3-3h12a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Z");
}

.ya5qky4nj {
  d: path("M8 5h.01a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2m3 0h.01a1 1 0 0 1 0 2H11a1 1 0 0 1 0-2M4 8h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2m4 7a4 4 0 1 1 8 0a4 4 0 0 1-8 0m5.843-.778a2 2 0 1 0-3.684 1.555a2 2 0 0 0 3.684-1.555");
}

</style>
