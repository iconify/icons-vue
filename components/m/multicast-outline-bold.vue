<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zuquf0b8s"/><path class="lymn1951z"/><path class="t6hm3zb9t"/><path class="qkyv2jo2z"/><path class="m1k1s7nte"/><path class="th_-hsbei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:multicast-outline-bold" /></template>
<style>
.lymn1951z {
  d: path("M6 12h4");
}

.m1k1s7nte {
  d: path("M10 12h10");
}

.qkyv2jo2z {
  d: path("M10 5h10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t6hm3zb9t {
  d: path("M10 5v14");
}

.th_-hsbei {
  d: path("M10 19h10");
}

.zuquf0b8s {
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
