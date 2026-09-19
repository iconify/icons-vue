<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q4zx45b8w"/><path class="m5m4oibzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mon-espace" /></template>
<style>
.m5m4oibzn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.103 12.691A3.3 3.3 0 0 1 7.8 15.993a3.3 3.3 0 0 1-3.3-3.303a3.3 3.3 0 0 1 3.301-3.3a3.3 3.3 0 0 1 3.302 3.301m17.767 5.264a4.452 4.456 0 0 1-4.451 4.456a4.452 4.456 0 0 1-4.452-4.456a4.452 4.456 0 0 1 4.452-4.456a4.452 4.456 0 0 1 4.452 4.456M16.466 31.467c-.616-1.16.102-3.382 1.064-4.68c1.165-1.573 3.285-2.725 6.976-2.725c3.692 0 5.812 1.152 6.977 2.725c.962 1.298 1.68 3.52 1.064 4.68c-.938 1.763-4.925 1.923-8.04 1.923c-3.116 0-7.103-.16-8.04-1.923");
}

.q4zx45b8w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.34 10.595c4.345-3.25 11.36-6.86 14.166-6.86c3.85 0 15.625 6.798 17.55 10.132c1.925 3.335 1.925 16.931 0 20.266v0c-1.925 3.334-13.7 10.132-17.55 10.132S8.882 37.467 6.956 34.133c-1.68-2.911-1.893-13.641-.64-18.54");
}

</style>
