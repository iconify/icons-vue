<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uk0t-uscc"/><path class="be0q8_h3l"/><path class="dj_1fq25r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vaccine-sticker" /></template>
<style>
.be0q8_h3l {
  d: path("m18.899 17.101l-1.798 1.798a.794.794 0 0 1-1.351-.649l.117-1.057a1.5 1.5 0 0 1 1.326-1.326l1.057-.117a.794.794 0 0 1 .649 1.351");
}

.dj_1fq25r {
  fill: currentColor;
  d: path("m11.838 8.441l.239.484a1.5 1.5 0 0 0 1.129.82l.534.078a.655.655 0 0 1 .363 1.118l-.386.377a1.5 1.5 0 0 0-.432 1.327l.092.532a.655.655 0 0 1-.951.691l-.478-.251a1.5 1.5 0 0 0-1.396 0l-.478.251a.655.655 0 0 1-.951-.691l.092-.532a1.5 1.5 0 0 0-.432-1.327l-.386-.377a.655.655 0 0 1 .363-1.118l.534-.078a1.5 1.5 0 0 0 1.129-.82l.239-.484a.655.655 0 0 1 1.176 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uk0t-uscc {
  d: path("M15.5 20.5a9 9 0 1 1 5-5");
}

</style>
