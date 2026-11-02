<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u19l_rz7c"/><path class="iphxmvb_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-off-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iphxmvb_n {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 8a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2h1c.64 0 1.36.36 2 1l2 2c.369.369 1-.262 1-1v-4m0-6V6c0-.738-.631-1.369-1-1l-1 1M2 2l20 20");
}

.u19l_rz7c {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 18c0 .898-.572 1.928-1.521 2.089a1.34 1.34 0 0 1-1.186-.382l-2-2C9.98 17.395 9.468 17 9 17H8a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3h1c.468 0 .98-.395 1.293-.707l2-2c.31-.311.752-.456 1.186-.382C14.428 4.072 15 5.102 15 6Z");
}

</style>
