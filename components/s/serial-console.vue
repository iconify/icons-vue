<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rldj8sp1g"/><path class="sh2lehlyo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:serial-console" /></template>
<style>
.rldj8sp1g {
  d: path("M12.2 19H2.5V3H20v8.7");
}

.sh2lehlyo {
  d: path("m6.5 8l3 3l-3 3m4 0H13m3.5.5V17m3-2.5V17M15 17h6v1.5a3 3 0 0 1-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
