<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a5fjbaboy"/><path class="n6-2knb3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-check-bulk" /></template>
<style>
.a5fjbaboy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m10.933 13.519l4.299-5.159a1 1 0 1 1 1.536 1.28l-5 6a1 1 0 0 1-1.475.067l-3-3a.999.999 0 1 1 1.414-1.414Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.n6-2knb3w {
  d: path("M2 5a3 3 0 0 1 3-3h1a1 1 0 0 1 0 2H5a.997.997 0 0 0-1 1v1a1 1 0 0 1-2 0Zm12-3a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Zm5 0a3 3 0 0 1 3 3v1a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1h-1a1 1 0 0 1 0-2ZM2 10a1 1 0 0 1 2 0v4a1 1 0 0 1-2 0Zm20 4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0ZM5 22a3 3 0 0 1-3-3v-1a1 1 0 0 1 2 0v1a1 1 0 0 0 1 1h1a1 1 0 0 1 0 2Zm17-3a3 3 0 0 1-3 3h-1a1 1 0 0 1 0-2h1a1 1 0 0 0 1-1v-1a1 1 0 0 1 2 0Zm-12 3a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2Z");
}

</style>
