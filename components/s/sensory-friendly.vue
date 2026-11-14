<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4em6e4rg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sensory-friendly" /></template>
<style>
.l4em6e4rg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 12v1.438q-1.5.531-1.5 2.562v2.5q0 2.75 2.75 2.75t2.75-2.75V16q0-2.622-2.5-2.744V12q0-2.796 1.977-4.773T12 5.25t4.773 1.977T18.75 12v1.256q-2.5.122-2.5 2.744v2.5q0 2.75 2.75 2.75t2.75-2.75V16q0-2.031-1.5-2.562V12q0-3.417-2.416-5.834T12 3.75T6.166 6.166Q3.75 8.583 3.75 12m7.834 7.124Q9 17.401 9 15.25q0-2.5 2.25-2.5q.345 0 .75.272q.405-.272.75-.272q2.25 0 2.25 2.5q0 2.151-2.584 3.874q-.092.062-.199.094q-.106.032-.217.032t-.217-.032t-.199-.094");
}

</style>
