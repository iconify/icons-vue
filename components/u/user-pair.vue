<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="xba6ksakw"/><path class="nwaf0togn"/><circle class="wutjzvb8z"/><path class="ad8msd38f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-pair" /></template>
<style>
.ad8msd38f {
  d: path("M15.25 20.25h5a.75.75 0 0 0 .75-.75c0-3.42-1.57-6-3.25-6s-3.25 2.58-3.25 6a.75.75 0 0 0 .75.75M12 9.97c-.12 0-.25-.04-.34-.12c-.81-.71-1.67-1.46-1.67-2.48c0-.62.47-1.12 1.05-1.12c.4 0 .74.22.96.56c.22-.34.56-.56.96-.56c.59 0 1.05.5 1.05 1.12c0 1.02-.87 1.77-1.67 2.48c-.09.08-.22.12-.34.12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nwaf0togn {
  d: path("M3.75 20.25h5a.75.75 0 0 0 .75-.75c0-3.42-1.57-6-3.25-6S3 16.08 3 19.5a.75.75 0 0 0 .75.75");
}

.wutjzvb8z {
  cx: 17.75px;
  cy: 8px;
  r: 2.75px;
}

.xba6ksakw {
  cx: 6.25px;
  cy: 8px;
  r: 2.75px;
}

</style>
