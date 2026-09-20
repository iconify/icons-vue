<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="vw5y5vbsr"/><path class="o5pd3cb4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:printer-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.o5pd3cb4a {
  d: path("M214.67 72H200V40a8 8 0 0 0-8-8H64a8 8 0 0 0-8 8v32H41.33C27.36 72 16 82.77 16 96v80a8 8 0 0 0 8 8h32v32a8 8 0 0 0 8 8h128a8 8 0 0 0 8-8v-32h32a8 8 0 0 0 8-8V96c0-13.23-11.36-24-25.33-24M72 48h112v24H72Zm112 160H72v-48h112Zm40-40h-24v-16a8 8 0 0 0-8-8H64a8 8 0 0 0-8 8v16H32V96c0-4.41 4.19-8 9.33-8h173.34c5.14 0 9.33 3.59 9.33 8Zm-24-52a12 12 0 1 1-12-12a12 12 0 0 1 12 12");
}

.vw5y5vbsr {
  d: path("M232 96v80h-40v-24H64v24H24V96c0-8.84 7.76-16 17.33-16h173.34c9.57 0 17.33 7.16 17.33 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
