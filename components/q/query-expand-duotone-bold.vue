<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ipy94dbtd"/><path class="gh5uw2bqw"/><path class="avddsacmh"/><path class="mjobmmu8w"/><path class="y0676ebxw"/><path class="e7pgrp-wx"/><path class="y5__l6b-e"/><path class="cabegubdh"/><path class="ltxni2ncy"/><path class="gy18-zqeb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:query-expand-duotone-bold" /></template>
<style>
.avddsacmh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 5h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cabegubdh {
  d: path("M14 5h7");
}

.e7pgrp-wx {
  d: path("M2 12h6");
}

.gh5uw2bqw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 10 2.5 2.5L9 15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gy18-zqeb {
  d: path("M14 19h7");
}

.ipy94dbtd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ltxni2ncy {
  d: path("M14 12h7");
}

.mjobmmu8w {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.y0676ebxw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 19h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y5__l6b-e {
  d: path("m9 10 2.5 2.5L9 15");
}

</style>
