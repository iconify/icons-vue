<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="k66tt2kvs"/><path class="jik2yirrk"/><path class="dn6v61b9t"/><path class="mlbrz3ncq"/><path class="h6e5_kbbf"/><path class="n787bfb7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:radio-line-duotone" /></template>
<style>
.dn6v61b9t {
  d: path("M9 17C9 17.8284 8.32843 18.5 7.5 18.5C6.67157 18.5 6 17.8284 6 17C6 16.1716 6.67157 15.5 7.5 15.5C8.32843 15.5 9 16.1716 9 17Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.h6e5_kbbf {
  d: path("M13 17H18");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jik2yirrk {
  d: path("M7 13H17C18.1046 13 19 12.1046 19 11C19 9.89543 18.1046 9 17 9H7C5.89543 9 5 9.89543 5 11C5 12.1046 5.89543 13 7 13Z");
}

.k66tt2kvs {
  d: path("M10 22H14C17.7712 22 19.6569 22 20.8284 20.8284C22 19.6569 22 17.7712 22 14C22 10.2288 22 8.34315 20.8284 7.17157C19.6569 6 17.7712 6 14 6H10C6.22876 6 4.34315 6 3.17157 7.17157C2 8.34315 2 10.2288 2 14C2 17.7712 2 19.6569 3.17157 20.8284C4.34315 22 6.22876 22 10 22Z");
}

.mlbrz3ncq {
  d: path("M15 11.5V13");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.n787bfb7v {
  d: path("M6.5 6L15 2");
}

</style>
