<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="rpmktxbnw"/><path class="f25as5v8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:photo-camera" /></template>
<style>
.f25as5v8l {
  d: path("M6.5 11.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 0 0-7 0m5 0a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0");
}

.n1lsf0bnc {
  fill: currentColor;
  fill-rule: evenodd;
}

.rpmktxbnw {
  d: path("M5.696 5.078L5.398 6H4.5a3 3 0 0 0-3 3v6a3 3 0 0 0 3 3h11a3 3 0 0 0 3-3V9a3 3 0 0 0-3-3h-.899l-.297-.922A3 3 0 0 0 11.449 3H8.55a3 3 0 0 0-2.855 2.078M4.5 8h2.354L7.6 5.693A1 1 0 0 1 8.551 5h2.898a1 1 0 0 1 .951.693L13.145 8H15.5a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-11a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1");
}

</style>
