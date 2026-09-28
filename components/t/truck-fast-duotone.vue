<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u51ofac4q"/><path class="fmffh550t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:truck-fast-duotone" /></template>
<style>
.fmffh550t {
  d: path("M2 4L11 4M2 8L8 8M2 12L5 12M9 18C9 19.1046 8.1046 20 7 20C5.8954 20 5 19.1046 5 18C5 16.8954 5.8954 16 7 16C8.1046 16 9 16.8954 9 18ZM19 18C19 19.1046 18.1046 20 17 20C15.8954 20 15 19.1046 15 18C15 16.8954 15.8954 16 17 16C18.1046 16 19 16.8954 19 18Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u51ofac4q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1 4C1 3.44772 1.44772 3 2 3L11 3C13.209139 3 15 4.790861 15 7L16.585787 7C17.11622 7 17.624928 7.210714 18 7.585786L22.414214 12C22.789286 12.375072 23 12.88378 23 13.414213L23 17C23 18.104569 22.104569 19 21 19L3 19C1.895431 19 1 18.104569 1 17L1 4Z");
  stroke: none;
}

</style>
