<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="mmre-hlzn"/><path class="ye0kv3bao"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rudder-sharp" /></template>
<style>
.mmre-hlzn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 10V3.5m-6 0h9.5M11 10h6.5v11.25H11v-1Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.ye0kv3bao {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.25 13h.01");
}

</style>
