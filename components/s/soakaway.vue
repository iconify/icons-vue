<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lk6-p1t6l"/><path class="j3jr4jbaw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:soakaway" /></template>
<style>
.j3jr4jbaw {
  d: path("M12 2.5S9.75 5.25 9.75 7a2.25 2.25 0 0 0 4.5 0c0-1.75-2.25-4.5-2.25-4.5Zm-3 17h.01m2.99 1h.01m2.99-1h.01");
}

.lk6-p1t6l {
  d: path("M2 7.5h3.5l2.5 8h8l2.5-8H22");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
