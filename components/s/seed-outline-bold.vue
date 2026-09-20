<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rxj7i8-nj"/><path class="tklpoac2f"/><path class="qtw0m9brk"/><path class="a58s2rq6q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:seed-outline-bold" /></template>
<style>
.a58s2rq6q {
  d: path("m12 11 4 -4");
}

.qtw0m9brk {
  d: path("M12 8 8 4");
}

.rxj7i8-nj {
  d: path("M9 18a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tklpoac2f {
  d: path("M12 5v10");
}

</style>
