<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pnmesxbkv"/><path class="vz1kxy-md"/><path class="y9_petz-w"/><path class="c2qrdqggu"/><path class="um24rnbdo"/><path class="iasoq4jgl"/><path class="n18nhnn8h"/><path class="pb5_a4buv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wi-fi-router-round-line-duotone" /></template>
<style>
.c2qrdqggu {
  d: path("M8.5 15C8.5 15.8284 7.82843 16.5 7 16.5C6.17157 16.5 5.5 15.8284 5.5 15C5.5 14.1716 6.17157 13.5 7 13.5C7.82843 13.5 8.5 14.1716 8.5 15Z");
}

.iasoq4jgl {
  d: path("M21.5833 5.39702C20.7574 3.40286 18.7924 2 16.4996 2C14.2069 2 12.2419 3.40286 11.416 5.39702");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n18nhnn8h {
  d: path("M19.3806 6.65811C19.0167 5.41107 17.865 4.5 16.5004 4.5C15.1358 4.5 13.984 5.41107 13.6201 6.65811");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.pb5_a4buv {
  stroke-linejoin: round;
  d: path("M16.5 7H16.5001");
}

.pnmesxbkv {
  d: path("M2 15C2 12.2386 4.23858 10 7 10H17C19.7614 10 22 12.2386 22 15C22 17.7614 19.7614 20 17 20H7C4.23858 20 2 17.7614 2 15Z");
}

.um24rnbdo {
  d: path("M12 15H18.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.vz1kxy-md {
  d: path("M18 20L19 22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.y9_petz-w {
  d: path("M6 20L5 22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
