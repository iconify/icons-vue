<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="jf60lda-p"/><path class="n5x9_qb5a"/><path class="ataj3m0cv"/><path class="meg5w9b_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:syllabus" /></template>
<style>
.ataj3m0cv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 11.5h.01M7.75 16h.01");
}

.jf60lda-p {
  width: 16.5px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.meg5w9b_w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 11.5h5.5m-5.5 4.5h4");
}

.n5x9_qb5a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 7h9.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
