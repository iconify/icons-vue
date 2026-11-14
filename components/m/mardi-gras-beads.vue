<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="soeqjkb-q"/><path class="ncn0lhrhp"/><path class="mqetclbsa"/><path class="wwt6fhbop"/><path class="vze32c11t"/><path class="i6d2byb6l"/><path class="l7lgnzb-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mardi-gras-beads" /></template>
<style>
.i6d2byb6l {
  d: path("M17.5 10.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.l7lgnzb-d {
  d: path("M18 7a1.75 1.75 0 1 0 3.5 0A1.75 1.75 0 1 0 18 7Z");
}

.mqetclbsa {
  d: path("M4.5 13.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM3 10.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.ncn0lhrhp {
  d: path("M7 16.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.soeqjkb-q {
  d: path("M10.25 17.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vze32c11t {
  d: path("M16 13.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.wwt6fhbop {
  d: path("M2.5 7A1.75 1.75 0 1 0 6 7a1.75 1.75 0 1 0-3.5 0Zm11 9.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

</style>
