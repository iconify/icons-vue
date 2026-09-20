<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i_kjavbri"/><path class="nilwl-6aj"/><path class="qtxvlht3c"/><path class="gl3o38_gx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:type-infer-outline-regular" /></template>
<style>
.gl3o38_gx {
  d: path("M8 21h8");
}

.i_kjavbri {
  d: path("m8.5 3 -5 5 5 5");
}

.nilwl-6aj {
  d: path("m15.5 3 5 5 -5 5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qtxvlht3c {
  d: path("M8 17h8");
}

</style>
