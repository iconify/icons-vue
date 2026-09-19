<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l90j8nqtf"/><path class="nnrbefcza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:status-sticker-saver" /></template>
<style>
.l90j8nqtf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.018 2.503c-16.335.018-26.69 17.52-18.842 31.846L2.527 45.484l11.135-2.649c12.301 6.748 27.663.092 31.152-13.497S38.047 2.516 24.018 2.503m0 9.474v20.761");
}

.nnrbefcza {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.398 22.357l-10.38 10.381l-10.381-10.381M34.398 36.02H13.637");
}

</style>
