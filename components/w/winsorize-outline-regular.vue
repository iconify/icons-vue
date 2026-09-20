<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sjev68umd"/><path class="oe-98mb0w"/><path class="vdq8lyksd"/><path class="vhnbtvbtn"/><path class="xyj-l9cjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:winsorize-outline-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oe-98mb0w {
  d: path("M12 6v12");
}

.sjev68umd {
  d: path("M6 11v7");
}

.vdq8lyksd {
  d: path("M18 12v6");
}

.vhnbtvbtn {
  d: path("M3 8h18");
}

.xyj-l9cjp {
  d: path("M3 18h18");
}

</style>
