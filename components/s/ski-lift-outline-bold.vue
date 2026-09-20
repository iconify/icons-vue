<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ywch90sba"/><path class="ilk2gccex"/><path class="v35i90uku"/><path class="k2ge1hzsr"/><path class="qqj79abfc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ski-lift-outline-bold" /></template>
<style>
.ilk2gccex {
  d: path("M7 8v4");
}

.k2ge1hzsr {
  d: path("M15 15v4");
}

.qqj79abfc {
  d: path("M13 19v3h4v-3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v35i90uku {
  d: path("M5 12v3h4v-3");
}

.ywch90sba {
  d: path("m3 4 16 16");
}

</style>
