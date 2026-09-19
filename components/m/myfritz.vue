<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cday3e3-t"/><path class="z1qm9x-fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myfritz" /></template>
<style>
.cday3e3-t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38 5.5H9c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.z1qm9x-fc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.935 36.322v-9.294l4.652 9.304l4.652-9.29v9.29m4.652 0l-2.478-6.164m4.652 0l-2.953 8.373a1.4 1.4 0 0 1-1.316.931h-.383M5 24h37M23.464 10.791v7.918M10 10.791h3.959M10 14.75h2.573M10 10.791v7.918m6.077 0V10.79h2.591c1.466 0 2.654 1.19 2.654 2.66s-1.188 2.658-2.653 2.658h-2.592m2.592.001l2.591 2.598m4.347-7.916h5.245m-2.622 7.918v-7.918m4.525 0H38l-5.245 7.918H38");
}

</style>
