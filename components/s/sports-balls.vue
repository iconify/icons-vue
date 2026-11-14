<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dad3i6b9n"/><path class="dlhh_-b-g"/><path class="zfs5kz1tz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sports-balls" /></template>
<style>
.dad3i6b9n {
  d: path("M7 7.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

.dlhh_-b-g {
  d: path("M2.5 16.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zfs5kz1tz {
  d: path("M11.5 16.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0ZM7 7.5h10M2.75 15Q7 16.5 6 21.25m10.5-4.75h.01");
}

</style>
