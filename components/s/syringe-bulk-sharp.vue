<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="e4k92q85o"/><path class="fojj_mq6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:syringe-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.e4k92q85o {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m9.707 10.293l4 4a1 1 0 0 1 0 1.414l-3 3a1 1 0 0 1-1.414 0l-4-4a1 1 0 0 1 0-1.414l3-3a1 1 0 0 1 1.414 0");
}

.fojj_mq6y {
  d: path("m16.707 3.293l4 4a.999.999 0 1 1-1.414 1.414L18 7.414L16.414 9l2.293 2.293a.999.999 0 1 1-1.414 1.414L17 12.414l-6.293 6.293a1 1 0 0 1-1.414 0L8 17.414l-3.293 3.293a.999.999 0 1 1-1.414-1.414L6.586 16l-1.293-1.293a1 1 0 0 1 0-1.414L11.586 7l-.293-.293a.999.999 0 1 1 1.414-1.414L15 7.586L16.586 6l-1.293-1.293a.999.999 0 1 1 1.414-1.414M13 8.414L7.414 14L10 16.586L15.586 11Z");
}

</style>
