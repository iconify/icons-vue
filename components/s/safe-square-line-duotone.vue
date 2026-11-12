<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xvjk-cbox"/><path class="ik06bsbra"/><path class="p39idcbfe"/><path class="wto5qfb3t"/><path class="doa2mfb8h"/><path class="ro6cy7xlh"/><path class="ca0rzv6fc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:safe-square-line-duotone" /></template>
<style>
.ca0rzv6fc {
  d: path("M18 16L16.5 14.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.doa2mfb8h {
  d: path("M10 16L11.5 14.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ik06bsbra {
  d: path("M6 7L6 17");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p39idcbfe {
  d: path("M14 15C12.3431 15 11 13.6569 11 12C11 10.3431 12.3431 9 14 9C15.6569 9 17 10.3431 17 12C17 13.6569 15.6569 15 14 15Z");
}

.ro6cy7xlh {
  d: path("M11.5 9.5L10 8");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.wto5qfb3t {
  d: path("M16.5 9.5L18 8");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.xvjk-cbox {
  d: path("M12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22Z");
}

</style>
