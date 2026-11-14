<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lsxr55beo"/><path class="t5blqhb3d"/><path class="ah55kfbgu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sales-per-square-foot" /></template>
<style>
.ah55kfbgu {
  d: path("M19.25 16.75C19 16.25 18.6 16 18 16c-.7 0-1.25.4-1.25 1c0 1.25 2.5.75 2.5 2c0 .6-.55 1-1.25 1c-.6 0-1-.25-1.25-.75");
}

.lsxr55beo {
  d: path("M11.6 16.5H7.5v-14h14v10M4.5 3v13M3.25 4.25L4.5 3l1.25 1.25m-2.5 10.5L4.5 16l1.25-1.25M8 19.5h3.6m-2.35-1.25L8 19.5l1.25 1.25");
}

.t5blqhb3d {
  d: path("M14.25 18a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
