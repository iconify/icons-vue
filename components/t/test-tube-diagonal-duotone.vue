<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lm5qi0b5y"/><path class="s-xpk0xxq"/><path class="t4orpzvpd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:test-tube-diagonal-duotone" /></template>
<style>
.lm5qi0b5y {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15.5176 2.2533L18.8696 4.4359C19.4364 4.805 19.7783 5.4355 19.7783 6.1119C19.7783 6.4994 19.6658 6.8785 19.4544 7.2032L10.3521 21.1826C9.6139 22.3162 8.3528 23 7 23C4.7909 23 3 21.2091 3 19C3 18.2251 3.2251 17.4668 3.6479 16.8174L12.7502 2.838C13.1193 2.2712 13.7499 1.9293 14.4263 1.9293C14.8137 1.9293 15.1929 2.0419 15.5176 2.2533Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s-xpk0xxq {
  fill: currentColor;
  d: path("M6.7847 12L16.331 12L10.3521 21.1826C9.6139 22.3162 8.3528 23 7 23C4.7909 23 3 21.2091 3 19C3 18.2251 3.2251 17.4668 3.6479 16.8174Z");
  stroke: none;
}

.t4orpzvpd {
  d: path("M13.2959 2L20 6.3652");
}

</style>
