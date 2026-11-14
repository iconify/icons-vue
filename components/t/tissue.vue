<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nxw4upb9y"/><path class="a0rcw8bfq"/><path class="o-drj00_n"/><path class="zcvimmp5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tissue" /></template>
<style>
.a0rcw8bfq {
  d: path("M10 3.25C9 6 10.5 9 9.75 12.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nxw4upb9y {
  d: path("M4 6c2-3 6-3.25 9-2.5c4-.75 7.5 1 8 5c.5 3.5-.75 6.5 0 9.5c-1 3-5 3.5-9 2.75c-4 .75-8 .25-9-3.25C2.5 14 3.5 10 4 6");
}

.o-drj00_n {
  d: path("M3.25 13c2.25-.75 4.25.5 6.5-.5c2.75-1 6.25.5 11-1");
}

.zcvimmp5a {
  d: path("M14.5 12.25C13.5 15 15 18 14 21M5.25 8a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m9-.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m-7 9.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m9.25-.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
