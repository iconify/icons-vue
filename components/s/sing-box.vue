<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g5_47d9jm"/><path class="a74a44blk"/><path class="a9wt37oqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sing-box" /></template>
<style>
.a74a44blk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.41 17.012v13.976c0 .498-.229.995-.686 1.314l-15.49 10.81a2.16 2.16 0 0 1-2.468 0l-15.49-10.81a1.59 1.59 0 0 1-.685-1.314h0V17.012M24 29.524V43.5");
}

.a9wt37oqs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.873 12.49L30.27 25.622v3.804a.858.858 0 0 0 1.336.712l4.4-2.966c.296-.2.473-.533.473-.89V21.29L18.083 8.156");
}

.g5_47d9jm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.724 15.698l-15.49-10.81a2.16 2.16 0 0 0-2.468 0l-15.49 10.81a1.603 1.603 0 0 0 0 2.628l15.49 10.81a2.16 2.16 0 0 0 2.468 0l15.49-10.81a1.603 1.603 0 0 0 0-2.628");
}

</style>
