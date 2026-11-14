<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t2pi5cc4y"/><path class="aq1hz_8ct"/><path class="g09lsz-kr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:podcast-episode" /></template>
<style>
.aq1hz_8ct {
  d: path("M15.5 2.5V6H19m-8.25 7a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.g09lsz-kr {
  d: path("M9.172 15.828a4 4 0 1 1 5.656 0M12 14.25v4.5");
}

.t2pi5cc4y {
  d: path("M5 2.5h10.5L19 6v15.5H5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
