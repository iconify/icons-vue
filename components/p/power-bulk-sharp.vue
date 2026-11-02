<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mcgw_ybxo"/><path class="ez5ltz-ki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:power-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ez5ltz-ki {
  d: path("M13 3v8a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0m4.64 3.232a8.813 8.813 0 0 1-9.302 14.786a8.82 8.82 0 0 1-5.072-6.849A8.8 8.8 0 0 1 6.36 6.232a1 1 0 0 1 1.28 1.536a6.75 6.75 0 0 0-1.694 2.108a6.84 6.84 0 0 0-.464 5.105a6.8 6.8 0 0 0 3.72 4.229a6.8 6.8 0 0 0 5.63-.012a6.815 6.815 0 0 0 1.528-11.43a1 1 0 1 1 1.28-1.536");
}

.mcgw_ybxo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4.19 13a7.81 7.81 0 1 1 15.622 0A7.81 7.81 0 1 1 4.19 13");
}

</style>
