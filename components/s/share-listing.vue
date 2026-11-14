<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nn12l5b8y"/><path class="l1398kb5c"/><path class="b-6pju0tt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:share-listing" /></template>
<style>
.b-6pju0tt {
  d: path("m19.25 14.25l2.25 2.25l-2.25 2.25");
}

.l1398kb5c {
  d: path("m5.5 10.5l4-4l4 4v4.786m-.986 1.214H5.5v-6M16 9h3m-3 3h1.6m-3.1 9.5v-2a3 3 0 0 1 3-3H21");
}

.nn12l5b8y {
  d: path("M11.7 19.5H2.5v-15h19v8.1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
