<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n175ejbuu"/><path class="z_98kffks"/><path class="pq36swk7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pointer-rotate" /></template>
<style>
.n175ejbuu {
  d: path("M7.5 14.5v-6a1.5 1.5 0 0 1 3 0v-1a1.5 1.5 0 0 1 3 0V13a1.25 1.25 0 0 1 2.5 0a1.25 1.25 0 0 1 2.5 0v3.5c0 2.9-1.75 5-4.5 5h-1.5c-1.6 0-2.75-.6-3.5-1.75l-4.25-5a1.5 1.5 0 0 1 2-2Zm3-6V12");
}

.pq36swk7c {
  d: path("m13.5 5.25l2.25.75l.5-2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z_98kffks {
  d: path("M4.862 6.948A6 6 0 0 1 15.696 6");
}

</style>
