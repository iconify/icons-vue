<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mk5xfob2d"/><path class="r3i4ax27t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:settings-restore" /></template>
<style>
.mk5xfob2d {
  d: path("M5 12a8 8 0 1 1 4 6.928");
}

.r3i4ax27t {
  d: path("m2 9l3 3l3-3m4.733.859l.103-1.05h1.328l.103 1.05l1.136.656l.961-.435l.664 1.15l-.857.614v1.312l.857.614l-.664 1.15l-.961-.435l-1.136.656l-.103 1.05h-1.328l-.103-1.05l-1.136-.656l-.961.435l-.664-1.15l.857-.614v-1.312l-.857-.614l.664-1.15l.961.435Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
