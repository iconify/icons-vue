<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s3jkkrb6o"/><path class="uhjffo8gx"/><path class="uf-j07bpp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sightseeing-outline-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s3jkkrb6o {
  d: path("M2 9a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.uf-j07bpp {
  d: path("m8 7 2.5 -2.5h3L16 7");
}

.uhjffo8gx {
  d: path("M8 13.5a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
