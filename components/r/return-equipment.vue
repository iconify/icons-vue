<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fj0lpnxka"/><path class="g7y-qhuko"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:return-equipment" /></template>
<style>
.fj0lpnxka {
  d: path("M12.2 15H4.5V3h15v10.3M15.8 21H2.5v-3.5h9.7m6 3.5h-.5m3.3.25v-2.5a2.5 2.5 0 0 0-2.5-2.5H15");
}

.g7y-qhuko {
  d: path("M16.75 14.5L15 16.25L16.75 18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
