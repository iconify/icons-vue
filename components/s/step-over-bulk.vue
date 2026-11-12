<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fy4bg0wvb"/><path class="a323bvbxy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:step-over-bulk" /></template>
<style>
.a323bvbxy {
  d: path("m18.99 10.596l1.303-1.303a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0l-3-3a.999.999 0 1 1 1.414-1.414l1.278 1.278a6 6 0 0 0-2.851-4.687a6 6 0 0 0-5.469-.413A5.99 5.99 0 0 0 5 11a1 1 0 0 1-2 0a8 8 0 0 1 7.798-7.997a8 8 0 0 1 8.192 7.593");
}

.cuyn6tgcc {
  fill: currentColor;
}

.fy4bg0wvb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15.236 17.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m2.057 1.875a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414");
}

</style>
