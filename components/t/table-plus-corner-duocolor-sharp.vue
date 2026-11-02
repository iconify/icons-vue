<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m0z_pzvrc"/><path class="kyxgkzbxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-plus-corner-duocolor-sharp" /></template>
<style>
.kyxgkzbxh {
  d: path("M12 4h8v5M9 20H4V4h8M4 9h16M4 15h5m3-11v5");
}

.m0z_pzvrc {
  stroke-opacity: 0.4;
  d: path("M13 17h8m-4-4v8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
