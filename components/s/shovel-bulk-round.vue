<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gzt9nzzpo"/><path class="g8zp34bpo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shovel-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g8zp34bpo {
  d: path("m15.707 4.293l2 1.999v.001l2 2a.999.999 0 1 1-1.414 1.414L17 8.414l-5.293 5.293a.999.999 0 1 1-1.414-1.414L15.586 7l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

.gzt9nzzpo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m9.707 10.293l4 4a2.41 2.41 0 0 1 0 3.414c-.37.37-.791.693-1.26.928A3.26 3.26 0 0 1 11 19H9a4 4 0 0 1-4-4v-2c0-1.039.578-1.992 1.293-2.707a2.41 2.41 0 0 1 3.414 0");
}

</style>
