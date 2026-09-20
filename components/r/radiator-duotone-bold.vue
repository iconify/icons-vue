<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mcqij090l"/><path class="s3lwy2n0b"/><path class="zto18nxmz"/><path class="wew0vnk_n"/><path class="uue3xmbwl"/><path class="kst16lb8k"/><path class="yjd2gm3-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:radiator-duotone-bold" /></template>
<style>
.kst16lb8k {
  d: path("M6 18.5V21");
}

.mcqij090l {
  fill: currentColor;
  d: path("M3 7a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
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

.s3lwy2n0b {
  d: path("M3 7a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.uue3xmbwl {
  d: path("M15 5v14");
}

.wew0vnk_n {
  d: path("M12 5v14");
}

.yjd2gm3-w {
  d: path("M18 18.5V21");
}

.zto18nxmz {
  d: path("M9 5v14");
}

</style>
