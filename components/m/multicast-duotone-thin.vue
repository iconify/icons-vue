<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rsea1pbos"/><path class="x705m_bfs"/><path class="dsuvylbkz"/><path class="m30t5bbty"/><path class="s74cfob_f"/><path class="t_lc87pkr"/><path class="zuquf0b8s"/><path class="lymn1951z"/><path class="t6hm3zb9t"/><path class="qkyv2jo2z"/><path class="m1k1s7nte"/><path class="th_-hsbei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:multicast-duotone-thin" /></template>
<style>
.dsuvylbkz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lymn1951z {
  d: path("M6 12h4");
}

.m1k1s7nte {
  d: path("M10 12h10");
}

.m30t5bbty {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 5h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qkyv2jo2z {
  d: path("M10 5h10");
}

.rsea1pbos {
  fill: currentColor;
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s74cfob_f {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t_lc87pkr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 19h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t6hm3zb9t {
  d: path("M10 5v14");
}

.th_-hsbei {
  d: path("M10 19h10");
}

.x705m_bfs {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 12h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zuquf0b8s {
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
