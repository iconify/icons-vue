<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hgz3jvbnt"/><path class="sj7hrub0u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:note-lock" /></template>
<style>
.hgz3jvbnt {
  d: path("M4 6a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v10l-4 4H6a2 2 0 0 1-2-2Z");
}

.sj7hrub0u {
  d: path("M16 20v-2.5a1.5 1.5 0 0 1 1.5-1.5H20M8.5 10.5h6V15h-6Zm1.25 0v-1a1.75 1.75 0 0 1 3.5 0v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
