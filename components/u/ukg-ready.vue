<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o8c4onbwa"/><path class="u8b-x2b7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ukg-ready" /></template>
<style>
.o8c4onbwa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.14 23.95c0 2.41-1.95 4.36-4.36 4.36s-4.359-1.95-4.359-4.36s1.95-4.36 4.36-4.36s4.36 1.95 4.36 4.36M24.37 6.781c-1.76-1.76-4.65-1.71-6.33.17c-1.58 1.75-1.34 4.5.33 6.18L29.24 24L18.37 34.868c-1.67 1.67-1.92 4.42-.33 6.18a4.354 4.354 0 0 0 6.33.17L41.579 24.01z");
}

.u8b-x2b7j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.409 30.16l-6.169-6.17l6.169-6.17");
}

</style>
