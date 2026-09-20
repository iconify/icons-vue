<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k-gv_lb9q"/><path class="bha7_zvaw"/><path class="jkpmfmxuy"/><path class="ez1_3xbuo"/><path class="ctidvybhh"/><path class="urdhk5jow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:recent-items-outline-bold" /></template>
<style>
.bha7_zvaw {
  d: path("M7 9.5V12");
}

.ctidvybhh {
  d: path("M14 13h7");
}

.ez1_3xbuo {
  d: path("M14 8h7");
}

.jkpmfmxuy {
  d: path("M7 12h2.5");
}

.k-gv_lb9q {
  d: path("M3 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.urdhk5jow {
  d: path("M14 18h5");
}

</style>
