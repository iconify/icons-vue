<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ftwsh098i"/><path class="uzrt0fbtk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:play-pause-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ftwsh098i {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m6.664 5.504l6 4a2.998 2.998 0 0 1 0 4.992l-6 4A3 3 0 0 1 2 16V8a3 3 0 0 1 4.664-2.496");
}

.uzrt0fbtk {
  d: path("M18 6v12a1 1 0 0 1-2 0V6a1 1 0 0 1 2 0m4 0v12a1 1 0 0 1-2 0V6a1 1 0 0 1 2 0");
}

</style>
