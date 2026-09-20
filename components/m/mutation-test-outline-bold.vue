<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k6nj2fbya"/><path class="pesxdybze"/><path class="s4ceatb9m"/><path class="f8057zb1p"/><path class="xqeoz9oav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mutation-test-outline-bold" /></template>
<style>
.f8057zb1p {
  d: path("M18 12h3");
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.pesxdybze {
  d: path("M3 12h7");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s4ceatb9m {
  d: path("M13 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.xqeoz9oav {
  d: path("m9 17 2 2 4 -4");
}

</style>
