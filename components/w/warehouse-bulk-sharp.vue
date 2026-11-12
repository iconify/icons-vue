<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="udru6813h"/><path class="syq-kg8rw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:warehouse-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.syq-kg8rw {
  d: path("M21 22H3a1 1 0 0 1 0-2h5v-7a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v7h5a1 1 0 0 1 0 2m-7-6v-2h-4v2Zm-4 4h4v-2h-4Z");
}

.udru6813h {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 21V10c0-.379.214-.725.553-.894l6-3A1 1 0 0 1 11 6h2c.155 0 .308.036.447.106l6 3A1 1 0 0 1 20 10v11a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1");
}

</style>
