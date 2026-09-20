<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="ot2t4wbih"/><path class="cwgbdsbkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:pentagram-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.cwgbdsbkm {
  d: path("M239.2 91.06A15.76 15.76 0 0 0 224 80h-61l-19.7-60.74a15.94 15.94 0 0 0-30.46-.05L93.06 80H32a16 16 0 0 0-9.38 29l49.47 35.59L53.14 203A15.77 15.77 0 0 0 59 220.91a15.77 15.77 0 0 0 18.78 0L128 184.77l50.24 36.14A16 16 0 0 0 202.86 203l-19-58.46l49.5-35.62a15.76 15.76 0 0 0 5.84-17.86M128 24.15L146.12 80h-36.24ZM32 96h55.87L77.3 128.58Zm36.36 112l17.39-53.59l28.55 20.54Zm22.57-69.57L104.69 96h46.62l13.76 42.39L128 165.06ZM187.64 208l-45.91-33l28.55-20.54Zm-8.94-79.38L168.13 96H224Z");
}

.ot2t4wbih {
  d: path("m228.69 102.47l-54.21 39l20.77 64a8 8 0 0 1-12.31 8.95L128 174.91l-54.94 39.53a8 8 0 0 1-12.31-8.95l20.77-64l-54.21-39A8 8 0 0 1 32 88h66.87l21.52-66.32a7.94 7.94 0 0 1 15.22 0L157.13 88H224a8 8 0 0 1 4.69 14.47");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
