<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e5f144b0c"/><path class="u2eln1pnd"/><path class="hk2eim99s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-diary" /></template>
<style>
.e5f144b0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.707 12.362h19.88a2.553 2.553 0 0 1 2.56 2.56V40.94a2.553 2.553 0 0 1-2.56 2.559h-19.88a2.553 2.553 0 0 1-2.56-2.559V14.92a2.553 2.553 0 0 1 2.56-2.56z");
}

.hk2eim99s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.878 8.859l.157-2.442a2.04 2.04 0 0 1 2.174-1.912h0l17.457 1.123a2.043 2.043 0 0 1 1.912 2.174l-.293 4.561M21.438 24.68h10.418m-10.418 2.277h10.418");
}

.u2eln1pnd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.147 35.916H10.9a2.043 2.043 0 0 1-2.047-2.047V10.905c0-1.133.913-2.046 2.047-2.046h17.602c1.134 0 2.047.913 2.047 2.046v1.457");
}

</style>
