<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="pz54s8gnh"/><path class="zrnuaslnh"/><path class="vcm_t_brk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wire-stripper" /></template>
<style>
.pz54s8gnh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 4.75a2 2 0 0 1 2-2h.75v4.5h4.5v-4.5H15a2 2 0 0 1 2 2v4a5 5 0 0 1-10 0Z");
}

.vcm_t_brk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10 13.3l5.5 7.95M14 13.3l-5.5 7.95");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zrnuaslnh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 10.5h.01");
}

</style>
