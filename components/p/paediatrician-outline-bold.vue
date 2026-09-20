<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="myekf3bzc"/><path class="v1odfppiu"/><path class="k939z7b-y"/><path class="h903oobjg"/><path class="gb43o-b8h"/><path class="hzn91qbfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:paediatrician-outline-bold" /></template>
<style>
.gb43o-b8h {
  d: path("M17 2v6");
}

.h903oobjg {
  d: path("M13.5 18a3.5 3.5 0 0 1 7 0");
}

.hzn91qbfm {
  d: path("M14 5h6");
}

.k939z7b-y {
  d: path("M15 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.myekf3bzc {
  d: path("M4 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v1odfppiu {
  d: path("M2.5 17a4.5 4.5 0 0 1 9 0");
}

</style>
