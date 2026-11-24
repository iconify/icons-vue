<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nbbsvrbsx"/><path class="yl1ox_bbt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:silo-duocolor-sharp" /></template>
<style>
.nbbsvrbsx {
  stroke-opacity: 0.4;
  d: path("M4 13h8m-8 4h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yl1ox_bbt {
  d: path("M4 21V8a4 4 0 1 1 8 0v13m-9 0h18M12 8l8 4v9");
}

</style>
