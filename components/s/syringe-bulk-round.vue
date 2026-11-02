<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zfleigi8q"/><path class="u7tjjzyhq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:syringe-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.u7tjjzyhq {
  d: path("m16.707 3.293l4 4a.999.999 0 1 1-1.414 1.414L18 7.414L16.414 9l2.293 2.293a.999.999 0 1 1-1.414 1.414L17 12.414l-4.293 4.293a3.83 3.83 0 0 1-4.614.614l-3.386 3.386a.999.999 0 1 1-1.414-1.414l3.386-3.386a3.83 3.83 0 0 1 .614-4.614L11.586 7l-.293-.293a.999.999 0 1 1 1.414-1.414L15 7.586L16.586 6l-1.293-1.293a.999.999 0 1 1 1.414-1.414M13 8.414l-4.293 4.293a1.829 1.829 0 0 0 2.586 2.586L15.586 11Z");
}

.zfleigi8q {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m9.707 10.293l4 4a1 1 0 0 1 0 1.414l-1 1a3.828 3.828 0 0 1-5.414-5.414l1-1a1 1 0 0 1 1.414 0");
}

</style>
