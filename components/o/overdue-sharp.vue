<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="waa338bte"/><path class="lqt5w6d4w"/><path class="esi391bqf"/><path class="ic7qnlnrp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:overdue-sharp" /></template>
<style>
.esi391bqf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.5 13.75V17");
}

.ic7qnlnrp {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.5 20h.01");
}

.lqt5w6d4w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 14h.01M12 14h.01M8 17h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.waa338bte {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.75 20.25h-8v-15h16.5v6.5M3.75 10h16.5M8 2.75v4.5m8-4.5v4.5");
}

</style>
