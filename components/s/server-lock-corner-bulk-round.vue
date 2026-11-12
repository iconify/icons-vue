<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k645rez1q"/><path class="reiygsbcw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-lock-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k645rez1q {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 3h12a4 4 0 0 1 0 8H6a4 4 0 0 1 0-8m4 17a1 1 0 0 1-1 1H6a4 4 0 0 1 0-8h3a1 1 0 0 1 1 1Z");
}

.reiygsbcw {
  d: path("M7.01 6a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2ZM22 19a3 3 0 0 1-3 3h-4a3.004 3.004 0 0 1-3-3v-1c0-1.273.799-2.407 2-2.829v-.172A3 3 0 0 1 20 15v.171A3 3 0 0 1 22 18Zm-4-4a1 1 0 0 0-1-1h-.001a1 1 0 0 0-.712.299A.96.96 0 0 0 16 15ZM7.01 16a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Z");
}

</style>
