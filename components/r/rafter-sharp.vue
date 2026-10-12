<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unpsrzbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rafter-sharp" /></template>
<style>
.unpsrzbgl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 3.5h2.5v4h-2.5zm0 .6v3.4l-.37.47l-7.26 9.06l-.37.47v-4l.37-.47l7.26-9.06l.37-.47zm2.87-.13l7.26 9.06l.37.47v4l-.37-.47l-7.26-9.06l-.37-.47v-4zM5.25 14.5h13.5m-12.25 0V18m11-3.5V18M6.75 9.75h10.5");
}

</style>
