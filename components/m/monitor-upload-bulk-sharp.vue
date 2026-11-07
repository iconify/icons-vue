<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sq2a32-oo"/><path class="a27nelhgg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-upload-bulk-sharp" /></template>
<style>
.a27nelhgg {
  d: path("m8.293 9.293l3-3a1 1 0 0 1 1.414 0l3 3a.999.999 0 1 1-1.414 1.414L13 9.414V14a1 1 0 0 1-2 0V9.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414M15 21H9a1 1 0 0 1 0-2h6a1 1 0 0 1 0 2");
}

.cuyn6tgcc {
  fill: currentColor;
}

.sq2a32-oo {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 4a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v13a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Z");
}

</style>
