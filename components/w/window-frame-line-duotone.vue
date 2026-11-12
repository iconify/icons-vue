<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pw8f5c0fp"/><path class="rnmzmq59b"/><path class="qdnildxhg"/><path class="pgoacybzz"/><path class="ryg9aovix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:window-frame-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pgoacybzz {
  stroke-linejoin: round;
  d: path("M9 6H9.0001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.pw8f5c0fp {
  d: path("M2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12Z");
}

.qdnildxhg {
  stroke-linejoin: round;
  d: path("M12 6H12.0001");
}

.rnmzmq59b {
  d: path("M2 9.5H9M9 9.5H22M9 9.5V21.9799");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ryg9aovix {
  stroke-linejoin: round;
  d: path("M6 6H6.0001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
