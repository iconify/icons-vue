<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v2a16cblp"/><path class="rnyji3x5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wemeet" /></template>
<style>
.rnyji3x5i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.002 34.553l7.024-7.052L24 34.505l6.975-7.004l6.975 7.004l4.502-4.52a3.58 3.58 0 0 0 0-5.062l-11.43-11.476l-13.997 14.054V13.49");
}

.v2a16cblp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.002 34.553L5.547 30.08a3.58 3.58 0 0 1 0-5.062h0l11.478-11.525l6.974 7.004");
}

</style>
