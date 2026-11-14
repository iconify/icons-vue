<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r0hnsjk9l"/><path class="udkbltsxj"/><path class="zt_l7hb5d"/><path class="aij57pbql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mortgage-equity-release" /></template>
<style>
.aij57pbql {
  d: path("m15 21l5.25-5.25m-4-.25h4.25v4.25");
}

.r0hnsjk9l {
  d: path("M11.56 20.5H4v-10l8-7l8 7v1.54");
}

.udkbltsxj {
  d: path("M16 7V4h2v4.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zt_l7hb5d {
  fill: currentColor;
  d: path("M11.6 20.5H4v-7h9.4");
}

</style>
