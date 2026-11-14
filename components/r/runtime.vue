<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="atrgqtb0t"/><path class="qleqqk8bl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:runtime" /></template>
<style>
.atrgqtb0t {
  d: path("m9.908 4.798l.41-2.148h3.364l.41 2.148l3.099 1.789l2.065-.719l1.682 2.914l-1.654 1.429v3.578l1.654 1.429l-1.682 2.914l-2.065-.719l-3.099 1.789l-.41 2.148h-3.364l-.41-2.148l-3.099-1.789l-2.065.719l-1.682-2.914l1.654-1.429v-3.578L3.062 8.782l1.682-2.914l2.065.719Z");
}

.qleqqk8bl {
  d: path("m9.75 8l6.5 4l-6.5 4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
