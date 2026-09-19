<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pojdhdyot"/><path class="nmil-edqi"/><path class="dsz_wqb3s"/><path class="h4gcdnk7g"/><path class="x9edi-bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:story-plotter" /></template>
<style>
.dsz_wqb3s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.387 11.629V8.386c0-1.073.863-1.936 1.936-1.936h25.193c1.073 0 1.937.863 1.937 1.936V19.45c0 1.073.863 1.937 1.936 1.937h.175a1.93 1.93 0 0 0 1.936-1.924v-9.74h-4.047");
}

.h4gcdnk7g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.58 11.629V8.386c0-1.073.864-1.936 1.936-1.936m4.048 14.937h-5.83m-22.13-6.522h18.758v5.205H12.604zm0 8.398h5.166v5.205h-5.166zm7.733 2.615h11.22m-11.22 2.616h9.8m-.545-5.233h.389m-9.644 0h7.245");
}

.nmil-edqi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.5 33.514l33.106-3.31l.406 4.061l-33.105 3.31zm0 0l-3 2.332l3.403 1.691m26.724-6.697l.395 3.947m2.22-4.207l.395 3.946m-4.057 2.882v4.142H9.387v-1.5m0-8.922v-19.5H34.58v16.887");
}

.pojdhdyot {
  fill: currentColor;
  d: path("M32.857 38.81a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.x9edi-bha {
  fill: currentColor;
  d: path("M12.602 9.003a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m2.628 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m2.628 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0M27.6 38.81a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m2.629 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

</style>
