<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xp9gunb1g"/><path class="ttglnqcci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-star" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ttglnqcci {
  d: path("m12.625 6.625l.283.735a1.5 1.5 0 0 0 1.293.958l.872.062a.715.715 0 0 1 .427 1.245l-.593.534a1.5 1.5 0 0 0-.458 1.452l.176.764a.721.721 0 0 1-1.066.785l-.803-.469a1.5 1.5 0 0 0-1.512 0l-.803.469a.721.721 0 0 1-1.066-.785l.176-.764a1.5 1.5 0 0 0-.458-1.452L8.5 9.625a.715.715 0 0 1 .427-1.245l.872-.062a1.5 1.5 0 0 0 1.293-.958l.283-.735a.67.67 0 0 1 1.25 0");
}

.xp9gunb1g {
  d: path("M12 22c-3.5-3-8-7-8-12a8 8 0 0 1 16 0c0 5-4.5 9-8 12");
}

</style>
