<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i-jutlbmh"/><path class="k1w882-vz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:satellite-off" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i-jutlbmh {
  d: path("M12.489 8.553q.431.125.748.442l1.768 1.768q.164.165.28.366q.116.202.175.427m-3.891 3.907q-.229-.058-.434-.175t-.372-.283l-1.768-1.768q-.312-.312-.439-.736");
}

.k1w882-vz {
  d: path("m4.929 15.536l2.121-2.122a1.5 1.5 0 0 1 2.122 0l1.414 1.414a1.5 1.5 0 0 1 0 2.122l-2.122 2.121a1.5 1.5 0 0 1-2.121 0l-1.414-1.414a1.5 1.5 0 0 1 0-2.121m8.485-8.486l2.122-2.121a1.5 1.5 0 0 1 2.121 0l1.414 1.414a1.5 1.5 0 0 1 0 2.121l-2.121 2.122a1.5 1.5 0 0 1-2.122 0l-1.414-1.414a1.5 1.5 0 0 1 0-2.122M8.907 4.987q.55.228.971.65q.428.427.657.987M3.5 3.5l17 17");
}

</style>
