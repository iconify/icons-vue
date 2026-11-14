<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b0rw--baf"/><path class="rgv9_4bmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:press-badge-user" /></template>
<style>
.b0rw--baf {
  d: path("M11.5 21.5h-8v-16h13v5.7M8 5.5v-3h4v3");
}

.rgv9_4bmn {
  d: path("M7.5 11.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM7 17h4.5m4.5-1.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1.75 6c0-1.75 1.75-3 3.75-3s3.75 1.25 3.75 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
