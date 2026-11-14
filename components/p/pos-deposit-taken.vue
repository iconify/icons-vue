<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iolmqxfyw"/><path class="heakl5bjq"/><path class="i05p1zxqk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pos-deposit-taken" /></template>
<style>
.heakl5bjq {
  d: path("M9.25 10.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM6 10.5h.01m11.99 0h.01M14.25 18a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Z");
}

.i05p1zxqk {
  fill: currentColor;
  d: path("M18 14.25a3.75 3.75 0 0 1 0 7.5Z");
}

.iolmqxfyw {
  d: path("M11.5 17h-9V4h19v8.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
