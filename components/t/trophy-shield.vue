<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xkc8ejbjp"/><path class="g0atuvv5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:trophy-shield" /></template>
<style>
.g0atuvv5h {
  d: path("M9.5 8h5v2a2.5 2.5 0 0 1-5 0Zm2.5 4.5v3m-2 0h4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xkc8ejbjp {
  d: path("M12 2.5L19.5 5v6c0 5-3.5 8.5-7.5 10.5c-4-2-7.5-5.5-7.5-10.5V5Z");
}

</style>
