<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ku6osrbmt"/><path class="pgy6ixebd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tactics-board" /></template>
<style>
.ku6osrbmt {
  d: path("M2.5 2.5h19v15h-19Zm4.5 15l-2 4m12-4l2 4");
}

.pgy6ixebd {
  d: path("M5 13a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm10.75-7.75l3 3m-3 0l3-3m-7.75 7l2.25-2.75m-2 .25l2-.25l-.25 2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
