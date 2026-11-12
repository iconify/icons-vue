<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="n_npn5bge"/><path class="ko6o-6b9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tennis-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ko6o-6b9b {
  d: path("M7 3.33782C8.47087 2.48697 10.1786 2 12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 10.1786 2.48697 8.47087 3.33782 7");
}

.n_npn5bge {
  d: path("M13.195 2.07117C13.195 2.07117 12.9634 5.66988 15.4634 10C17.9634 14.3301 21.1958 15.9288 21.1958 15.9288M2.80273 8.07117C2.80273 8.07117 6.03515 9.66988 8.53515 14C11.0352 18.3301 10.8035 21.9288 10.8035 21.9288");
}

</style>
