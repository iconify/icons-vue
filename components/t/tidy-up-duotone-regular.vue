<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tlj36_-3d"/><path class="lhk-ji-wo"/><path class="lh_8lcb-x"/><path class="icvc39peu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tidy-up-duotone-regular" /></template>
<style>
.icvc39peu {
  d: path("m9 7 3 3 3 -3");
}

.lh_8lcb-x {
  d: path("M12 4v6");
}

.lhk-ji-wo {
  d: path("M5 12v8h14v-8Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tlj36_-3d {
  fill: currentColor;
  d: path("M5 12v8h14v-8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
