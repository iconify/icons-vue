<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gnq8duvln"/><path class="e_uya30ac"/><path class="rc20j6byk"/><path class="u8oheccad"/><path class="m-y6zjb5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:violin-duotone-bold" /></template>
<style>
.e_uya30ac {
  d: path("M12 21c-4 0 -8 -1.5 -8 -4s5 -3.5 5 -5 -3.5 -2 -3.5 -3.5S8 6 10 6h4c2 0 4.5 1 4.5 2.5S15 10.5 15 12s5 2.5 5 5 -4 4 -8 4");
}

.gnq8duvln {
  fill: currentColor;
  d: path("M12 21c-4 0 -8 -1.5 -8 -4s5 -3.5 5 -5 -3.5 -2 -3.5 -3.5S8 6 10 6h4c2 0 4.5 1 4.5 2.5S15 10.5 15 12s5 2.5 5 5 -4 4 -8 4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.m-y6zjb5q {
  d: path("M16 15v3");
}

.rc20j6byk {
  d: path("M12 2v4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u8oheccad {
  d: path("M8 15v3");
}

</style>
