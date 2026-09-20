<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c-pcdbceg"/><path class="cj5113wsg"/><path class="zk34t1b0y"/><path class="tuh74bcqx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rain-outline-regular" /></template>
<style>
.c-pcdbceg {
  d: path("M4 14a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 5a5.5 5.5 0 0 1 4.5 9Z");
}

.cj5113wsg {
  d: path("M7 16.5 9.5 19a2.5 2.5 0 0 1 -5 0Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tuh74bcqx {
  d: path("m17 16.5 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

.zk34t1b0y {
  d: path("m12 17.5 2.5 2.5a2.5 2.5 0 0 1 -5 0Z");
}

</style>
