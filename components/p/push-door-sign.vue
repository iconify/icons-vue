<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jcx262x8m"/><path class="smzb4-ibu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:push-door-sign" /></template>
<style>
.jcx262x8m {
  d: path("M9.5 2.5h12v19h-12Z");
}

.smzb4-ibu {
  d: path("M12.5 6h6v12h-6Zm-10 6H7m-2-2l2 2l-2 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
