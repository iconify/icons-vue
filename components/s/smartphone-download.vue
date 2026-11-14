<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p6oq9egqp"/><path class="vr6sjkbto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smartphone-download" /></template>
<style>
.p6oq9egqp {
  d: path("M6 2.5h12v19H6ZM10.5 18h3M12 6v5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vr6sjkbto {
  d: path("m9.5 9l2.5 2.5L14.5 9M9 14.5h6");
}

</style>
