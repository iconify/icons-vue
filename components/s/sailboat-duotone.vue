<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n34v4bcae"/><path class="jx-ijvbol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sailboat-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jx-ijvbol {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4 17l-1-5h18l-1 5M9 3v9m0-9l9 9H9zM2 20c.5.5 1 1 2 1c2 0 2-2 4-2s2 2 4 2s2-2 4-2s2 2 4 2c1 0 1.5-.5 2-1");
}

.n34v4bcae {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m9.707 2.293l9 9A1 1 0 0 1 18 13H9a1 1 0 0 1-1-1V3a1.002 1.002 0 0 1 1.707-.707");
}

</style>
