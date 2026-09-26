<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b_gf1sbty"/><path class="a6s4ubbfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:phone-missed-fill" /></template>
<style>
.a6s4ubbfu {
  d: path("M22 2L16 8M16 2L22 8");
}

.b_gf1sbty {
  fill: currentColor;
  d: path("M1 4C1 2.3431 2.3431 1 4 1L7 1C8.6569 1 10 2.3431 10 4L10 7C10 7.9443 9.5554 8.8334 8.8 9.4L8.3388 9.7459C9.6049 12.3156 11.6844 14.3951 14.2541 15.6612L14.6 15.2C15.1666 14.4446 16.0557 14 17 14L20 14C21.6569 14 23 15.3431 23 17L23 20C23 21.6569 21.6569 23 20 23C9.5066 23 1 14.4934 1 4Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
