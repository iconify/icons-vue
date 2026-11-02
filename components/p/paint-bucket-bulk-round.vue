<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gu0s_0bwe"/><path class="wwhor6wqd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paint-bucket-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gu0s_0bwe {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m11.707 5.293l6 6a1 1 0 0 1 0 1.414l-6 6a3.83 3.83 0 0 1-5.414 0l-2-2a3.83 3.83 0 0 1 0-5.414l6-6a1 1 0 0 1 1.414 0");
}

.wwhor6wqd {
  d: path("m8.707 2.293l3 3a.999.999 0 1 1-1.414 1.414l-3-3a.999.999 0 1 1 1.414-1.414M5 11h12a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2m17 8a3 3 0 1 1-6 0c0-.774.371-1.494.825-2.1c.436-.581.955-1.095 1.468-1.607a1 1 0 0 1 1.414 0c.983.982 2.292 2.233 2.293 3.707");
}

</style>
