<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rb4hcopdf"/><path class="o903avb-o"/><path class="jlj43xbts"/><path class="xrifsibej"/><path class="tldtqlb3m"/><path class="a1iadc4sf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:newspaper-duotone-bold" /></template>
<style>
.a1iadc4sf {
  d: path("M4 13h12");
}

.jlj43xbts {
  d: path("M18 9h4v8h-4");
}

.o903avb-o {
  d: path("M2 19V6h16v13Z");
}

.rb4hcopdf {
  fill: currentColor;
  d: path("M2 19V6h16v13Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tldtqlb3m {
  d: path("M10 13v4");
}

.xrifsibej {
  d: path("M4 10h12");
}

</style>
