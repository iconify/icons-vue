<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tvscirbaj"/><path class="ns1702rxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tennis-forehand" /></template>
<style>
.ns1702rxs {
  d: path("M3.25 12A10 10 0 0 1 10 3.25");
}

.tvscirbaj {
  d: path("M19.25 6a4.5 6 45 1 1-8.5 8.5a4.5 6 45 1 1 8.5-8.5Zm-8.5 8.5L5 20.25m8.5-14.5l6 6m-9-3l6 6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
