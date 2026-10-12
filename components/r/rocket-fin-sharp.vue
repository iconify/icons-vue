<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="palxpjb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rocket-fin-sharp" /></template>
<style>
.palxpjb8i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 17.5v-11c0-2.25 1.5-3.75 3-3.75s3 1.5 3 3.75v11Zm-.56-7.5l-7.38 6.5L5 17v4.25l.69-.3l7.12-3.15l.69-.3v-8zM16 17.5l-.25 3h2.5l-.25-3Z");
}

</style>
