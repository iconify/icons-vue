<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p0s1grb-m"/><path class="keycpyibe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:towel-rack-sharp-fill" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.keycpyibe {
  d: path("M20 2C20.552 2 21 2.45 21 3V6H23V8H21V16H8V2H20Z");
}

.p0s1grb-m {
  d: path("M21 18V21C21 21.55 20.552 22 20 22H9C8.448 22 8 21.55 8 21V18H21ZM6 16H4C3.448 16 3 15.55 3 15V8H1V6H3V5.5C3 3.79 4.374 2.34 6 2.04V16Z");
}

</style>
