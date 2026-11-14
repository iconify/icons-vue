<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s5c3fyb1a"/><path class="q0vasms1a"/><path class="s3dl2vdxc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:notification-home" /></template>
<style>
.q0vasms1a {
  d: path("M8.5 20.5v-5h4v2.9m0 .2v1.9");
}

.s3dl2vdxc {
  fill: currentColor;
  d: path("M15.25 18.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.s5c3fyb1a {
  d: path("M12.772 20.5H2.5v-10L11 3l8.5 7.5v2.028");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
