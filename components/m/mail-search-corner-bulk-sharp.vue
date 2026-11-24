<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q_-3ftbqj"/><path class="elp654bdb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-search-corner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.elp654bdb {
  d: path("M3.707 4.293L9.414 10h5.172l5.707-5.707a.999.999 0 1 1 1.414 1.414l-4.941 4.941l-.001.001l-1.058 1.058A1 1 0 0 1 15 12H9a1 1 0 0 1-.707-.293l-6-6a.999.999 0 1 1 1.414-1.414m17.614 15.614l1.386 1.386a.999.999 0 1 1-1.414 1.414l-1.386-1.386a3.83 3.83 0 1 1 1.414-1.414m-1.626-1.218a1.83 1.83 0 1 0-3.39-1.376a1.83 1.83 0 0 0 3.39 1.376");
}

.q_-3ftbqj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 19V5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-9v7a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1");
}

</style>
