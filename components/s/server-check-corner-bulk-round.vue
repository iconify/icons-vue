<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k645rez1q"/><path class="mmius025n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-check-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k645rez1q {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 3h12a4 4 0 0 1 0 8H6a4 4 0 0 1 0-8m4 17a1 1 0 0 1-1 1H6a4 4 0 0 1 0-8h3a1 1 0 0 1 1 1Z");
}

.mmius025n {
  d: path("M7.01 6a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Zm6.697 10.293l2.226 2.226l4.299-5.159a1 1 0 1 1 1.536 1.28l-5 6a1 1 0 0 1-1.475.067l-3-3a.999.999 0 1 1 1.414-1.414M7.01 16a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Z");
}

</style>
