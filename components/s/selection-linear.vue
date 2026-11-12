<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f8v5_fa-m"/><path class="jqqpebcxi"/><path class="s1i1vtodc"/><path class="fkex6abdo"/><path class="o9kntxagx"/><path class="xnwp-xx6w"/><path class="u9onkhwwo"/><path class="e69g47h7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:selection-linear" /></template>
<style>
.e69g47h7j {
  d: path("M4 6V18");
}

.f8v5_fa-m {
  d: path("M6 4C6 5.105 5.1046 6 4 6C2.8954 6 2 5.105 2 4C2 2.895 2.8954 2 4 2C5.1046 2 6 2.895 6 4Z");
}

.fkex6abdo {
  d: path("M22 20C22 21.105 21.1046 22 20 22C18.8954 22 18 21.105 18 20C18 18.895 18.8954 18 20 18C21.1046 18 22 18.895 22 20Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jqqpebcxi {
  d: path("M6 20C6 21.105 5.1046 22 4 22C2.8954 22 2 21.105 2 20C2 18.895 2.8954 18 4 18C5.1046 18 6 18.895 6 20Z");
}

.o9kntxagx {
  d: path("M6 20H18");
}

.s1i1vtodc {
  d: path("M22 4C22 5.105 21.1046 6 20 6C18.8954 6 18 5.105 18 4C18 2.895 18.8954 2 20 2C21.1046 2 22 2.895 22 4Z");
}

.u9onkhwwo {
  d: path("M20 18V6");
}

.xnwp-xx6w {
  d: path("M18 4H6");
}

</style>
