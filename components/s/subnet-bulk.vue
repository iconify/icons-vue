<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l5e3y4lol"/><path class="ktv-e3hgx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:subnet-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ktv-e3hgx {
  d: path("M13 11a1 1 0 0 1-2 0V7a1 1 0 0 1 2 0Zm-5.99 4a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Zm5 0a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Zm5 0a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2Z");
}

.l5e3y4lol {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 5a3 3 0 1 1 6 0a3 3 0 0 1-6 0m-7 8a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>
