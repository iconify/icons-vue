<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="m7ukxtbvq"/><path class="xv6kuw8hw"/><path class="ko6o-6b9b"/><path class="xme672xeh"/><path class="vnda1s8vz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smart-vacuum-cleaner-broken" /></template>
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

.m7ukxtbvq {
  d: path("M12 12C10.3431 12 9 10.6569 9 9C9 7.34315 10.3431 6 12 6C13.6569 6 15 7.34315 15 9");
}

.vnda1s8vz {
  d: path("M7.35462 20.8579C6.84413 21.2601 6.19984 21.5001 5.49951 21.5001C3.84266 21.5001 2.49951 20.1569 2.49951 18.5001C2.49951 17.7996 2.73954 17.1553 3.14183 16.6448");
}

.xme672xeh {
  d: path("M16.6451 20.8579C17.1555 21.26 17.7998 21.4999 18.5 21.4999C20.1569 21.4999 21.5 20.1568 21.5 18.4999C21.5 17.7997 21.2601 17.1555 20.858 16.645");
}

.xv6kuw8hw {
  d: path("M12 18V16");
}

</style>
