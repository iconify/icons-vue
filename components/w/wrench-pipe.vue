<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x-yi62b5p"/><path class="cqd5rdbxp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wrench-pipe" /></template>
<style>
.cqd5rdbxp {
  d: path("m12.77 6.91l2.35 2.34q.42.42-.01.84l-.21.22q-.43.42 0 .84l1.27 1.28q.43.42.01.84l-1.64 1.64q-.42.42-.84 0l-3.4-3.4q-.42-.42 0-.85l1.28-1.27q.42-.43 0-.85l-.22-.22q-.42-.42 0-.84l.57-.57q.42-.42.84 0m.82 4.71l-.71.7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x-yi62b5p {
  d: path("M10.76 11.97L4.4 18.33l1.77 1.77l6.36-6.36m3.01-4.07l1.94-1.94l-3.18-3.18l1.59-1.6l4.95 4.95l-4.6 4.6");
}

</style>
