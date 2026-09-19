<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qosnzbfbb"/><circle class="lhacb8beo"/><path class="ut1tvjx2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tack" /></template>
<style>
.lhacb8beo {
  cx: 10.435px;
  cy: 18.118px;
  r: 4.353px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qosnzbfbb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.49 38.558c-3.676-5.46-9.08-8.391-17.413-8.391s-13.737 2.93-17.412 8.391c-1.179 1.75.22 3.942 2.33 3.942h30.163c2.111 0 3.51-2.191 2.331-3.942Zm-17.413-8.391V5.5m-2.902 2.902h5.804m-5.804 7.255h5.804m-5.804 7.255h5.804");
}

.ut1tvjx2u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.258 14.348l-2.176-3.77m6.529 11.31l5.079 8.796");
}

</style>
