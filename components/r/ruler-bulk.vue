<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="eb8ng0bxb"/><path class="owjh7hb_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ruler-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.eb8ng0bxb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m8.293 8.293l5-5a2.414 2.414 0 0 1 3.414 0l4 4a2.414 2.414 0 0 1 0 3.414l-10 10a2.414 2.414 0 0 1-3.414 0l-4-4a2.414 2.414 0 0 1 0-3.414Z");
}

.owjh7hb_g {
  d: path("M15.707 6.293a.999.999 0 1 1-1.414 1.414l-2-2a.999.999 0 1 1 1.414-1.414Zm-4 4a.999.999 0 1 1-1.414 1.414l-2-2a.999.999 0 1 1 1.414-1.414Zm-4 4a.999.999 0 1 1-1.414 1.414l-2-2a.999.999 0 1 1 1.414-1.414Z");
}

</style>
