<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bc6akkb6o"/><path class="z2c-hu7is"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ungroup-duotone-sharp" /></template>
<style>
.bc6akkb6o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 5v5H5V5Zm7 9v5h-7v-5Z");
}

.ft5dv1b6b {
  fill: none;
}

.z2c-hu7is {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 5h7v5H5zm7 9h7v5h-7z");
}

</style>
