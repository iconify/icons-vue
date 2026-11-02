<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yc3o1pbgs"/><path class="sz4oh-bxb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pin-off-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.sz4oh-bxb {
  d: path("m4.707 1.293l18 18a.999.999 0 1 1-1.414 1.414l-18-18a.999.999 0 1 1 1.414-1.414M13 17v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0");
}

.yc3o1pbgs {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 9.757L8.243 2H16a3 3 0 1 1 0 6ZM5.438 3.438l13.976 13.976A2 2 0 0 1 18 18H6a2 2 0 0 1-2-2v-1c0-.802.379-1.451.985-1.956c.47-.391 1.024-.666 1.568-.938c.392-.197.843-.405 1.182-.687c.128-.107.265-.24.265-.419V8a3.001 3.001 0 0 1-2.562-4.562");
}

</style>
