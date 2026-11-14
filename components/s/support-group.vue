<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xzrjjybin"/><path class="b4so3rbxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:support-group" /></template>
<style>
.b4so3rbxo {
  fill: currentColor;
  d: path("M12 16.5s-2.25-1.5-2.25-3c0-.75.5-1.5 1.25-1.5c.5 0 .75.25 1 .75c.25-.5.5-.75 1-.75c.75 0 1.25.75 1.25 1.5c0 1.5-2.25 3-2.25 3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xzrjjybin {
  d: path("M10.25 4.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM8.75 9.5C8.75 8 10.25 7 12 7s3.25 1 3.25 2.5M3.5 13.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM2 19c0-1.5 1.5-2.5 3.25-2.5s3.25 1 3.25 2.5m8.5-5.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM15.5 19c0-1.5 1.5-2.5 3.25-2.5S22 17.5 22 19");
}

</style>
