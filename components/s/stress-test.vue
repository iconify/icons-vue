<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="spysxctlp"/><path class="l7jmqhbnl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stress-test" /></template>
<style>
.l7jmqhbnl {
  d: path("M2.5 18.5h14l3-10.5h-3");
}

.spysxctlp {
  d: path("M7.5 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2 3l-1 4.5m-3 3.5l3-3.5l2.5 3.5M6.5 9l2.75-1L12 10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
