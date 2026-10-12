<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="f8fh7-bys"/><path class="ye0kv3bao"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rudder" /></template>
<style>
.f8fh7-bys {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 10V3.5m-6 0h9.5M11 10h5.5a1 1 0 0 1 1 1v6.25c0 2.2-1.8 4-4 4H12a1 1 0 0 1-1-1Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ye0kv3bao {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.25 13h.01");
}

</style>
