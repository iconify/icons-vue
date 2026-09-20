<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mvvbl7zxc"/><path class="vhnbtvbtn"/><path class="spg3og_ww"/><path class="f6kbfx-8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:recycle-bin-outline-bold" /></template>
<style>
.f6kbfx-8d {
  d: path("m9 17 3 -3 3 3");
}

.mvvbl7zxc {
  d: path("M6 8v13h12V8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.spg3og_ww {
  d: path("M9 8V5h6v3");
}

.vhnbtvbtn {
  d: path("M3 8h18");
}

</style>
