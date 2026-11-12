<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xvjk-cbox"/><path class="g626xxb-k"/><path class="gms528h1j"/><path class="qdnildxhg"/><path class="yup5k1aiy"/><path class="aqe2mdwjw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:window-frame-linear" /></template>
<style>
.aqe2mdwjw {
  stroke-linejoin: round;
  d: path("M6 6H6.0001");
}

.g626xxb-k {
  d: path("M2 9.5H22");
}

.gms528h1j {
  d: path("M9 21.9797L9 9.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qdnildxhg {
  stroke-linejoin: round;
  d: path("M12 6H12.0001");
}

.xvjk-cbox {
  d: path("M12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22Z");
}

.yup5k1aiy {
  stroke-linejoin: round;
  d: path("M9 6H9.0001");
}

</style>
