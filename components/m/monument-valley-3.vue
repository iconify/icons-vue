<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="f8ktbhs-i"/><path class="ms-8t5bnt"/><path class="adbnz636z"/><path class="yd7q96b0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:monument-valley-3" /></template>
<style>
.adbnz636z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.357 25.416c-.444 1.281-1.737 2.7-2.457 3.422a.78.78 0 0 0-.059 1.044c3.004 3.601 6.996 3.746 11.324 1.56c5.062-2.557-.12-6.827-.822-7.42");
}

.f8ktbhs-i {
  cx: 25.621px;
  cy: 14.59px;
  r: 4.59px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ms-8t5bnt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.326 18.85c-1.694-.676-2.883-2.33-2.883-4.26s1.189-3.583 2.883-4.267m-5.732 2.065L11 6.335s.96 3.7 1.439 6.645l8.63 1.023m15.93-6.606c-1.542-2.672-4.042-3.665-5.378-2.26s.617 5.993 1.918 9.042l-1.793 12.518m-7.04-7.609a96 96 0 0 1-4.833 3.298a.86.86 0 0 0-.294 1.137c.628 1.152 2.318 3.185 6.305 2.713l.36-5.104l2.671 3.391c.815-.765 1.128-1.94 1.24-2.536a.61.61 0 0 0-.233-.598l-3.085-2.374");
}

.yd7q96b0e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.701 32.606l-.38 10.392l2.012.502m4.207-11.333l-.234 10.374l2.146.228");
}

</style>
