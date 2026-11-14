<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o_srjzbdh"/><path class="bc75bcbgc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:photo-backup" /></template>
<style>
.bc75bcbgc {
  d: path("m6 10.5l3-3l3 3m0 0v8M9.5 16l2.5 2.5l2.5-2.5");
}

.o_srjzbdh {
  d: path("M6 2.5h12v8H6Zm-2.5 11V20A1.5 1.5 0 0 0 5 21.5h14a1.5 1.5 0 0 0 1.5-1.5v-6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
