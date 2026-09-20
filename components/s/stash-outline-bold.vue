<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="w2dozdlxo"/><path class="jotk81b5q"/><path class="f4naz_w9a"/><path class="nl66y9men"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stash-outline-bold" /></template>
<style>
.f4naz_w9a {
  d: path("m9 5 3 3 3 -3");
}

.jotk81b5q {
  d: path("M12 2v6");
}

.nl66y9men {
  d: path("M6 16h12");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w2dozdlxo {
  d: path("M2 14a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
