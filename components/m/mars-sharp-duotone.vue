<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lmrsucqff"/><path class="a5xy4h2vl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mars-sharp-duotone" /></template>
<style>
.a5xy4h2vl {
  d: path("M14.5 3L21 3L21 9.5M13.2426 10.7574L20.8243 3.1757");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lmrsucqff {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 15C16 18.866 12.866 22 9 22C5.134 22 2 18.866 2 15C2 11.134 5.134 8 9 8C12.866 8 16 11.134 16 15Z");
  stroke: none;
}

</style>
