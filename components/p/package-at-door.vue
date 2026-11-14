<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ooxztxw5f"/><path class="v7-hdlssd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:package-at-door" /></template>
<style>
.ooxztxw5f {
  d: path("M7 21.5v-18a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1V11M3 21.5h18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v7-hdlssd {
  d: path("M12 14h8v7.5h-8Zm4 0v3m-6-5.5h.01");
}

</style>
