<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bjqvxe9xp"/><path class="inyq0nfpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:nft-edit" /></template>
<style>
.bjqvxe9xp {
  d: path("M12.3 18H2.5V3h17v8.3");
}

.inyq0nfpi {
  d: path("M6 14.5L9.5 10l4.5 5m.5 6.5l.5-2.75l4.25-4.25a1.6 1.6 0 0 1 2.25 2.25L17.25 21Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
