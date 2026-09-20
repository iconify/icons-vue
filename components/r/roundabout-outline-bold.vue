<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g1du9hbaz"/><path class="c438ceftc"/><path class="rvoc0ob8r"/><path class="es-ot3p7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:roundabout-outline-bold" /></template>
<style>
.c438ceftc {
  d: path("M12 17v5");
}

.es-ot3p7v {
  d: path("M18 11h4");
}

.g1du9hbaz {
  d: path("M6 11a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

.rvoc0ob8r {
  d: path("M2 11h4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
