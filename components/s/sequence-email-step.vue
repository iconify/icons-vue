<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nq9olr_6y"/><path class="a020bperc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sequence-email-step" /></template>
<style>
.a020bperc {
  d: path("m2.5 7l9.5 6l9.5-6m-5.25 7.75L19.5 18l-3.25 3.25");
}

.nq9olr_6y {
  d: path("M15.1 18.5H2.5v-13h19v10.6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
