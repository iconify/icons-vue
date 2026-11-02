<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z_wdvrzjf"/><path class="ie0htj92u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sofa-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ie0htj92u {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 11v4a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2v-4a2 2 0 1 0-4 0a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2a2 2 0 1 0-4 0m2 6v2m14-2v2M12 5v8M5 9V7a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v2");
}

.z_wdvrzjf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 12h6a.997.997 0 0 0 1-1a3 3 0 0 1 .236-1.168A2.998 2.998 0 0 1 22 11v4a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-4a2.999 2.999 0 0 1 5.121-2.121c.274.273.493.596.643.953c.157.369.237.767.236 1.168a.997.997 0 0 0 1 1");
}

</style>
