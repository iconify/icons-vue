<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pl4bc-bkm"/><path class="i2emibcvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qr" /></template>
<style>
.i2emibcvf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.93 34.23a5.8 5.8 0 0 1-1.08-.86a5.4 5.4 0 0 1-1.22-3.74h4.6A5.4 5.4 0 0 1 33 33.37a5.8 5.8 0 0 1-1.08.86ZM5.5 34.22v8.28h8.28");
}

.pl4bc-bkm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.78 5.5H5.5v8.28m37 0V5.5h-8.28m0 37h8.28v-8.28m-31.95-7.81v11h11v-11zm3.22 3.22h4.6v4.6h-4.6Zm-3.22-19.08v11h11v-11zm3.22 3.22h4.6v4.6h-4.6Zm12.64-3.22v11h11v-11zm3.22 3.22h4.6v4.6h-4.6Zm2.3 23.68a5.8 5.8 0 0 0 3.47-2.1a8.37 8.37 0 0 0 2.05-5.72v-3.22h-11v3.22h0a8.4 8.4 0 0 0 2.05 5.72a5.8 5.8 0 0 0 3.43 2.1");
}

</style>
