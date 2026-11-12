<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o1224xbma"/><path class="b4p-u2c-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-text-bulk" /></template>
<style>
.b4p-u2c-w {
  d: path("M3 8h6a1 1 0 0 1 0 2H7v5a1 1 0 0 1-2 0v-5H3a1 1 0 0 1 0-2");
}

.cuyn6tgcc {
  fill: currentColor;
}

.o1224xbma {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 15a2 2 0 0 1-2-2v-2a2 2 0 0 1 2-2h1.586l3.707-3.707c.182-.182.398-.326.635-.424c.69-.286 1.561-.163 1.932.549c.093.18.141.379.14.582v12c.001.203-.047.402-.14.582c-.371.712-1.242.835-1.932.549a2 2 0 0 1-.635-.424L15.586 15Z");
}

</style>
