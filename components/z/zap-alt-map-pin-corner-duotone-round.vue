<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t-yeo2bvs"/><path class="z2r7yguil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-alt-map-pin-corner-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.t-yeo2bvs {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 10h1.394a7 7 0 0 0-3.309 4.915l-4.671 4.671a.581.581 0 0 1-.98-.538l1.241-5.584A1.206 1.206 0 0 0 4.5 12a.974.974 0 0 1-.891-1.371l2.863-6.441A2 2 0 0 1 8.3 3H12a1.16 1.16 0 0 1 1.008 1.736l-2.016 3.528A1.16 1.16 0 0 0 12 10m5 11c-1.574-1.051-2.999-3.053-3-5a3 3 0 1 1 6 0c-.001 1.947-1.426 3.949-3 5");
}

.z2r7yguil {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.394 10H12a1.16 1.16 0 0 1-1.008-1.736l2.016-3.528A1.16 1.16 0 0 0 12 3H8.3a2 2 0 0 0-1.828 1.188L3.61 10.629A.975.975 0 0 0 4.5 12c.77 0 1.342.713 1.175 1.464l-1.241 5.584c-.127.568.568.95.98.538l4.67-4.67M17 21c-1.5-1-3-3-3-5a3 3 0 0 1 6 0c0 2-1.5 4-3 5m0-5h.01");
}

</style>
