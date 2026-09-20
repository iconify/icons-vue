<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pek-tswzf"/><path class="dak2_9b1i"/><path class="hxoe7gx5p"/><path class="fyt8fyb5h"/><path class="x-egzxztr"/><path class="eg0ecwbhj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:score-distribution-outline-bold" /></template>
<style>
.dak2_9b1i {
  d: path("M8 9v8");
}

.eg0ecwbhj {
  d: path("M3 19.5h18");
}

.fyt8fyb5h {
  d: path("M16 9v8");
}

.hxoe7gx5p {
  d: path("M12 5v12");
}

.pek-tswzf {
  d: path("M4 13v4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x-egzxztr {
  d: path("M20 13v4");
}

</style>
