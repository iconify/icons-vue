<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tcvdb9wyg"/><path class="l172ypweo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:receipt-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.l172ypweo {
  d: path("M16 6a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm-8 4h4a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2");
}

.tcvdb9wyg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 2h16a1 1 0 0 1 1 1v18a1 1 0 0 1-1.447.894L16 20.118l-3.553 1.776a1 1 0 0 1-.894 0L8 20.118l-3.553 1.776A1 1 0 0 1 3 21V3a1 1 0 0 1 1-1");
}

</style>
