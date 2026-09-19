<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pk7yo7bir"/><path class="chk7obbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:torrent-search" /></template>
<style>
.chk7obbns {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.29 26.982a9.29 9.29 0 0 1-18.58.002v-.002a9.29 9.29 0 0 1 18.58 0m-2.746 6.596l5.048 5.048m-4.076-26.574h6.822m-28.676 0h6.823");
}

.pk7yo7bir {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.9 40.337C31.38 42.28 28.185 43.5 24 43.5c-7.194 0-11.459-3.6-14.396-8.294c-3.102-4.957-2.684-11.109-1.23-17.499l2.095-9.196c.72-3.165 2.602-3.998 4.232-4.003l2.673-.008l-1.723 14.615m16.698 0L30.626 4.5l2.673.008c1.63.005 3.511.838 4.232 4.003l2.094 9.196c1.455 6.39 1.873 12.542-1.229 17.499q-.534.855-1.13 1.657");
}

</style>
