<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8ci6achw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rocket-fin" /></template>
<style>
.a8ci6achw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 17.5v-11c0-2.25 1.5-3.75 3-3.75s3 1.5 3 3.75v11Zm-.56-7.5l-7.38 6.5Q5 17 5 17.75v2.75q0 .75.69.45l7.12-3.15q.69-.3.69-1.05v-6.5q0-.75-.56-.25M16 17.5l-.25 3h2.5l-.25-3Z");
}

</style>
