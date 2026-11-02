<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m5r0uhbmb"/><path class="em57w9skn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-off-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.em57w9skn {
  d: path("M1.293 2.707a.999.999 0 1 1 1.414-1.414l20 20a.999.999 0 1 1-1.414 1.414Z");
}

.m5r0uhbmb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m10.414 6.172l1.879-1.879c.31-.311.752-.456 1.186-.382C14.428 4.072 15 5.102 15 6v4.757Zm-3.286.956L15 15v3c0 .898-.572 1.928-1.521 2.089a1.34 1.34 0 0 1-1.186-.382l-2-2C9.98 17.395 9.468 17 9 17H8a3 3 0 0 1-3-3v-4c0-1.32.866-2.487 2.128-2.872");
}

</style>
