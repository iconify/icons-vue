<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ibql2392g"/><path class="rf5dn__pe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scale-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ibql2392g {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9.919 12.606a1 1 0 0 1 .004.779a4.25 4.25 0 0 1-7.846 0a1 1 0 0 1 .004-.779l3-7a.999.999 0 0 1 1.838 0Zm12 0a1 1 0 0 1 .004.779a4.251 4.251 0 0 1-7.846 0a1 1 0 0 1 .004-.779l3-7a.999.999 0 0 1 1.838 0Z");
}

.rf5dn__pe {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3v18m-4 0h8M6 6h12M6 6l3 7a3.25 3.25 0 0 1-6 0Zm12 0l3 7a3.25 3.25 0 0 1-6 0Z");
}

</style>
