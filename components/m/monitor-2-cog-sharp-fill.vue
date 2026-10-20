<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hew22xbcq"/><path class="iz4i7wbxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:monitor-2-cog-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hew22xbcq {
  fill: currentColor;
  d: path("M23 14L23 17C23 17.5523 22.5523 18 22 18L2 18C1.4477 18 1 17.5523 1 17L1 3C1 2.4477 1.4477 2 2 2L11 2L11 14L23 14Z");
  stroke: none;
}

.iz4i7wbxt {
  d: path("M12 17L12 21M7 21L17 21M20.6667 7C20.6667 8.4728 19.4728 9.6667 18 9.6667C16.5272 9.6667 15.3333 8.4728 15.3333 7C15.3333 5.5272 16.5272 4.3333 18 4.3333C19.4728 4.3333 20.6667 5.5272 20.6667 7ZM20.99 7L23 7M20.1142 9.1142L21.5355 10.5355M18 9.99L18 12M15.8858 9.1142L14.4645 10.5355M15.01 7L13 7M15.8858 4.8858L14.4645 3.4645M18 4.01L18 2M20.1142 4.8858L21.5355 3.4645");
}

</style>
