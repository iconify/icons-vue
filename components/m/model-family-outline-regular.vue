<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pus9z-bwo"/><path class="pfpu_3ppl"/><path class="k2i6ze2yw"/><path class="y7kkpcbjj"/><path class="oqx2fjbwx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:model-family-outline-regular" /></template>
<style>
.k2i6ze2yw {
  d: path("M6 15v-3h12v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oqx2fjbwx {
  d: path("m18 15 3 3 -3 3 -3 -3Z");
}

.pfpu_3ppl {
  d: path("M12 8v4");
}

.pus9z-bwo {
  d: path("m12 2 3 3 -3 3 -3 -3Z");
}

.y7kkpcbjj {
  d: path("m6 15 3 3 -3 3 -3 -3Z");
}

</style>
