<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="fmn8yub-d"><path class="dzj6vgs6n"/><path class="ual2p5bkq"/><path class="msbz7pb3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:secplayground" /></template>
<style>
.dzj6vgs6n {
  d: path("M4.989 10.576C4.573 20.52 10.134 37.236 24 42.901c13.866-5.664 19.427-22.382 19.011-32.325L24 5.1z");
}

.fmn8yub-d {
  fill: none;
  stroke: currentColor;
  stroke-dashoffset: 3;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.msbz7pb3w {
  d: path("M24 19.606a2.484 2.484 0 0 0-2.484 2.484a2.48 2.48 0 0 0 1.36 2.21l-1.041 4.207h4.33l-1.04-4.207a2.48 2.48 0 0 0 1.359-2.21A2.484 2.484 0 0 0 24 19.606m2.636 2.415h14.378");
}

.ual2p5bkq {
  d: path("M36.56 18.05q.204-1.365.3-2.819L24 11.406l-12.86 3.825c.756 11.661 6.973 19.004 12.86 21.38c3.001-1.21 6.088-3.713 8.493-7.42");
}

</style>
