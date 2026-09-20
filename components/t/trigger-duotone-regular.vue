<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n_ua_kbpf"/><path class="pdu-xkbsu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trigger-duotone-regular" /></template>
<style>
.n_ua_kbpf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 4 -7 7h5l-7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pdu-xkbsu {
  d: path("m16 4 -7 7h5l-7 7");
}

</style>
