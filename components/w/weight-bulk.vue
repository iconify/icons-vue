<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x3v5a9sxr"/><path class="algumwb1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:weight-bulk" /></template>
<style>
.algumwb1d {
  d: path("M9 6.019V6a3.004 3.004 0 0 1 3-3h.001c1.657.001 3 1.343 2.999 3v.001A3 3 0 0 1 12 9h-.001A3 3 0 0 1 9 6.019M11.999 5a1 1 0 0 0-.711.297a.96.96 0 0 0-.288.697v.011A1 1 0 1 0 12 5Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.x3v5a9sxr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 7h6c.732 0 1.416.341 1.927.852c.523.523.865 1.192 1.043 1.905l2 8c.253 1.014.015 2.242-.87 2.883c-.321.233-.703.36-1.1.36H6c-.397 0-.779-.127-1.1-.36c-.885-.641-1.123-1.869-.87-2.883l2-8c.178-.713.52-1.382 1.043-1.905C7.584 7.341 8.268 7 9 7");
}

</style>
