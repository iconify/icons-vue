<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kl5bgubbm"/><path class="ttgx8e9xc"/><path class="aponkpb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:miro" /></template>
<style>
.aponkpb4k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.786 5.5h5.322l9.392 5.916L33.358 42.5h-5.572l3.946-30.27z");
}

.kl5bgubbm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5h5.322l10.58 10.205L11.072 42.5H5.5l5.071-24.354z");
}

.ttgx8e9xc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.643 5.5h5.322l9.767 6.73l-9.517 30.27h-5.572l4.759-26.795z");
}

</style>
