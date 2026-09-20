<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a3eibhdgt"/><path class="z26gfvqcs"/><path class="s_9dtpvxy"/><path class="zl2kh1bxb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:travel-cover-outline-regular" /></template>
<style>
.a3eibhdgt {
  d: path("M4.5 9.5a7.5 7.5 0 0 1 15 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s_9dtpvxy {
  d: path("M8 15.5h8v5H8Z");
}

.z26gfvqcs {
  d: path("M4.5 9.5h15");
}

.zl2kh1bxb {
  d: path("M10 15.5v-3h4v3");
}

</style>
