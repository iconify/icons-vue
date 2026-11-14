<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n9ktarb6v"/><path class="esvtsu_dm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:press-roller" /></template>
<style>
.esvtsu_dm {
  d: path("M4 6a1.5 3 0 1 0 3 0a1.5 3 0 1 0-3 0Zm11.5 0l6-3.5M4 12h16v9.5H4Zm3.5 3.5h9m-9 3H13");
}

.n9ktarb6v {
  d: path("M5.5 3H14a1.5 3 0 0 1 0 6H5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
