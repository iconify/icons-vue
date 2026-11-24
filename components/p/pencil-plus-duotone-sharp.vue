<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nf2nfacxc"/><path class="fdno1hb4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-plus-duotone-sharp" /></template>
<style>
.fdno1hb4i {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 20v-3L16 7l3 3L9 20zm8-11l3 3M4 7h6M7 4v6");
}

.ft5dv1b6b {
  fill: none;
}

.nf2nfacxc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 17L16 7l3 3L9 20H6Z");
}

</style>
