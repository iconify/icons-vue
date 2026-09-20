<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o1yl8wb9e"/><path class="ior14cbcm"/><path class="skltlcb6w"/><path class="li-pabx_b"/><path class="eu2so4bxo"/><path class="z9ittvbis"/><path class="fd_pyz_no"/><path class="uh7f2-ziy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sun-set-duotone-thin" /></template>
<style>
.eu2so4bxo {
  d: path("M7 16a5 5 0 0 1 10 0");
}

.fd_pyz_no {
  d: path("M12 5v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ior14cbcm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.li-pabx_b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.5 6.5 12 9l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o1yl8wb9e {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 16a5 5 0 0 1 10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.skltlcb6w {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 5v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uh7f2-ziy {
  d: path("M9.5 6.5 12 9l2.5 -2.5");
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
