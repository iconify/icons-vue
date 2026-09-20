<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="od0i25b0q"/><path class="faufs1biu"/><path class="wyh0mccry"/><path class="xk62f6syw"/><path class="xaxtk6cud"/><path class="kj4zxsc0v"/><path class="ymfnpaceh"/><path class="c4g909b2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sync-duotone-regular" /></template>
<style>
.c4g909b2h {
  d: path("m12 17 -2.5 2.5L12 22");
}

.faufs1biu {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9.5 19.5H6a3 3 0 0 1 -3 -3v-9a3 3 0 0 1 3 -3h3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kj4zxsc0v {
  d: path("M9.5 19.5H6a3 3 0 0 1 -3 -3v-9a3 3 0 0 1 3 -3h3.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.od0i25b0q {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14.5 4.5H18a3 3 0 0 1 3 3v9a3 3 0 0 1 -3 3h-3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wyh0mccry {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 2 2.5 2.5L12 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xaxtk6cud {
  d: path("M14.5 4.5H18a3 3 0 0 1 3 3v9a3 3 0 0 1 -3 3h-3.5");
}

.xk62f6syw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m12 17 -2.5 2.5L12 22");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ymfnpaceh {
  d: path("m12 2 2.5 2.5L12 7");
}

</style>
