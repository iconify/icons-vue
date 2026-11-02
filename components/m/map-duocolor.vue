<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cf8r2lbua"/><path class="lv0xrmkke"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-duocolor" /></template>
<style>
.cf8r2lbua {
  stroke-opacity: 0.4;
  d: path("M9 3v15m6-12v15");
}

.lv0xrmkke {
  d: path("m9 3l6 3l4-2c.919-.46 2 .081 2 1v12c0 .613-.774 1.387-2 2l-4 2l-6-3l-4 2c-.919.46-2-.081-2-1V7c0-.613.774-1.387 2-2z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
