<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="efvf4pa8r"/><path class="nerdhbb1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-off-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.efvf4pa8r {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m15.243 11l-8-8H18a4 4 0 0 1 0 8ZM3.715 3.715L11 11H6a4.001 4.001 0 0 1-2.285-7.285M13 13l7.285 7.285A4 4 0 0 1 18 21H6a4 4 0 0 1 0-8Zm8.94 4.697L17.243 13H18a4 4 0 0 1 3.94 4.697");
}

.nerdhbb1y {
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414l-20-20a.999.999 0 1 1 1.414-1.414M7 16h.01a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2");
}

</style>
