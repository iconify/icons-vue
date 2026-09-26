<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="utox1qbcx"/><path class="jsoz6_bak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:monitor-duotone" /></template>
<style>
.jsoz6_bak {
  fill: currentColor;
  d: path("M5 3H19C21.20914 3 23 4.79086 23 7V13C23 15.20914 21.20914 17 19 17H5C2.79086 17 1 15.20914 1 13V7C1 4.79086 2.79086 3 5 3Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.utox1qbcx {
  stroke-opacity: 0.4;
  d: path("M12 16L12 20M8 20L16 20");
}

</style>
