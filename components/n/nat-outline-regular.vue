<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="otb2wbb6e"/><path class="wj4cfmbhq"/><path class="ms85c68gf"/><path class="i6ydbdc_n"/><path class="eud-3ptuk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:nat-outline-regular" /></template>
<style>
.eud-3ptuk {
  d: path("M15 12h7");
}

.i6ydbdc_n {
  d: path("m9 4 6 6v4l-6 6");
}

.ms85c68gf {
  d: path("M2 20h7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.otb2wbb6e {
  d: path("M2 4h7");
}

.wj4cfmbhq {
  d: path("M2 12h7");
}

</style>
