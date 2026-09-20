<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xaxtk6cud"/><path class="kj4zxsc0v"/><path class="ymfnpaceh"/><path class="c4g909b2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sync-outline-regular" /></template>
<style>
.c4g909b2h {
  d: path("m12 17 -2.5 2.5L12 22");
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

.xaxtk6cud {
  d: path("M14.5 4.5H18a3 3 0 0 1 3 3v9a3 3 0 0 1 -3 3h-3.5");
}

.ymfnpaceh {
  d: path("m12 2 2.5 2.5L12 7");
}

</style>
