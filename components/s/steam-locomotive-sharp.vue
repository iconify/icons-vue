<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="l1sihmvho"/><path class="d6zyorbpm"/><circle class="mid5xcbxi"/><circle class="hm61d-bvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:steam-locomotive-sharp" /></template>
<style>
.d6zyorbpm {
  d: path("M5.25 8.25h2v2.5h-2Zm14 7l2 2.5");
}

.hm61d-bvp {
  cx: 14.75px;
  cy: 17.75px;
  r: 2.5px;
}

.l1sihmvho {
  d: path("M2.75 15.25v-10h7v4h4.75v-3.5h3v3.5h2.75v6Z");
}

.mid5xcbxi {
  cx: 6.25px;
  cy: 17.75px;
  r: 2.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
