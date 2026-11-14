<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g04amgyuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wifi-off" /></template>
<style>
.g04amgyuk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 19.5h.01m-3.546-3.536q.463-.464 1.031-.792t1.199-.499m-5.765-2.244q.914-.914 2.03-1.565m6.561-1.248q.783.121 1.538.363q.755.243 1.462.601t1.349.823t1.202 1.026M2.358 8.009q.445-.374.918-.712m5.491-2.445q.419-.092.842-.161q.424-.068.851-.112t.856-.064t.858-.014q.429.004.857.034t.854.083q.426.054.848.133q.422.078.839.18t.827.228t.813.275t.796.321t.776.366t.754.41t.729.452t.702.493t.673.533M3.5 3.5l17 17");
}

</style>
