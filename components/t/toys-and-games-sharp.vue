<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye1upgn2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:toys-and-games-sharp" /></template>
<style>
.ye1upgn2v {
  fill: currentColor;
  d: path("M20 17.43V21H4v-3.558h.72q.274.177.6.272t.68.094q1.152 0 1.96-.809q.81-.809.81-1.96t-.81-1.961T6 12.269q-.296 0-.574.075t-.514.214H4V9h5.212v-.461q-.356-.414-.534-.943T8.5 6.5q0-1.471 1.015-2.485Q10.529 3 12 3t2.486 1.015T15.5 6.5q0 .567-.178 1.096t-.533.943V9H20v3.57h-.9q-.237-.145-.517-.223q-.281-.078-.583-.078q-1.152 0-1.96.809q-.81.809-.81 1.96T16.04 17t1.96.809q.36 0 .689-.098q.328-.097.603-.28z");
}

</style>
