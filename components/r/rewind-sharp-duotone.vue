<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq2_qrlix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rewind-sharp-duotone" /></template>
<style>
.cq2_qrlix {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 17.998L13.5417 12L22 6.002L22 17.998ZM10 17.998L2 12L10 6.002L10 17.998Z");
}

</style>
