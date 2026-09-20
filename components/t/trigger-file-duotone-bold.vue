<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bnbr32bwb"/><path class="cbojbkemm"/><path class="cfyvl-o0i"/><path class="mi_m6achy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trigger-file-duotone-bold" /></template>
<style>
.bnbr32bwb {
  fill: currentColor;
  d: path("M12 8v12H3V4h5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.cbojbkemm {
  d: path("M12 8v12H3V4h5Z");
}

.cfyvl-o0i {
  d: path("M16 12h4");
}

.mi_m6achy {
  d: path("m17 9 3 3 -3 3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
