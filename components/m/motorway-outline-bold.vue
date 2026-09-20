<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lwdt7zb5f"/><path class="pk1ekjvnl"/><path class="i2-ny_bzf"/><path class="vw_dl18nv"/><path class="ffs26fbkv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:motorway-outline-bold" /></template>
<style>
.ffs26fbkv {
  d: path("M12 17v4");
}

.i2-ny_bzf {
  d: path("M12 3v4");
}

.lwdt7zb5f {
  d: path("M4 2v20");
}

.pk1ekjvnl {
  d: path("M20 2v20");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vw_dl18nv {
  d: path("M12 10.5v3");
}

</style>
