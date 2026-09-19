<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="px2uy_uzv"/><path class="zsxmy_bdu"/><circle class="evhco2z0q"/><circle class="u6mn4w3os"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-videogame-asset" /></template>
<style>
.evhco2z0q {
  cx: 14.5px;
  cy: 13.5px;
  r: 1.5px;
  fill: currentColor;
}

.px2uy_uzv {
  fill: currentColor;
  d: path("M3 16h18V8H3zm15.5-7c.83 0 1.5.67 1.5 1.5s-.67 1.5-1.5 1.5s-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5m-4 3c.83 0 1.5.67 1.5 1.5s-.67 1.5-1.5 1.5s-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5M4 11h2V9h2v2h2v2H8v2H6v-2H4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.u6mn4w3os {
  cx: 18.5px;
  cy: 10.5px;
  r: 1.5px;
  fill: currentColor;
}

.zsxmy_bdu {
  fill: currentColor;
  d: path("M21 6H3c-1.1 0-2 .9-2 2v8c0 1.1.9 2 2 2h18c1.1 0 2-.9 2-2V8c0-1.1-.9-2-2-2m0 10H3V8h18zM6 15h2v-2h2v-2H8V9H6v2H4v2h2z");
}

</style>
