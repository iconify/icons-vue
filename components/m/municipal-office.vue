<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r3z06k2_s"/><path class="bs8rsxbpl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:municipal-office" /></template>
<style>
.bs8rsxbpl {
  d: path("M7.25 7h3.25v3.5H7.25Zm6.25 0h3.25v3.5H13.5Zm-4 14.5V15h5v6.5");
}

.r3z06k2_s {
  d: path("M2.5 3.5h19m-17 0v18h15v-18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
