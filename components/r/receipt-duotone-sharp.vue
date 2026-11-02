<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bepbfwb4i"/><path class="v-oxtcc7a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:receipt-duotone-sharp" /></template>
<style>
.bepbfwb4i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 3v18l-2-2l-2 2l-2-2l-2 2l-2-2l-2 2l-2-2l-2 2V3Z");
}

.ft5dv1b6b {
  fill: none;
}

.v-oxtcc7a {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h8v18l-2-2l-2 2l-2-2l-2 2l-2-2l-2 2l-2-2l-2 2V3zM8 7h8m-8 4h8m-8 4h4");
}

</style>
