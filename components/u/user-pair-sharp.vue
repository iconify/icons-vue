<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="xba6ksakw"/><path class="rq885wb3k"/><circle class="wutjzvb8z"/><path class="gtnx79bmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-pair-sharp" /></template>
<style>
.gtnx79bmn {
  d: path("M15.25 20.25H21v-.75c0-3.42-1.57-6-3.25-6s-3.25 2.58-3.25 6v.75zM12 9.97h-.205l-.135-.12l-1.67-1.464V6.25h1.648l.362.56l.362-.56h1.648v2.118L12.34 9.85l-.135.12z");
}

.rq885wb3k {
  d: path("M3.75 20.25H9.5v-.75c0-3.42-1.57-6-3.25-6S3 16.08 3 19.5v.75z");
}

.wutjzvb8z {
  cx: 17.75px;
  cy: 8px;
  r: 2.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xba6ksakw {
  cx: 6.25px;
  cy: 8px;
  r: 2.75px;
}

</style>
