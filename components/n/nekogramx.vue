<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ll0g54h-q"/><path class="mljbmhbjc"/><ellipse transform="rotate(-34.885 27.656 34.93)" class="loex0v9el"/><ellipse transform="rotate(-47.468 38.359 26.382)" class="hqq5nsbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nekogramx" /></template>
<style>
.hqq5nsbeq {
  cx: 38.359px;
  cy: 26.382px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.571px;
  ry: 1.727px;
}

.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.loex0v9el {
  cx: 27.656px;
  cy: 34.929px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.708px;
  ry: 1.878px;
}

.mljbmhbjc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.085 42.5c-.634-1.877-1.326-3.538-.87-5.744c-1.711-2.235-3.302-9.254-1.887-14.82c3.16.801 6.251 1.78 8.833 4.091c1.757-1.7 3.339-3.436 7.226-4.681c-1.369-3.999-1.632-7.4-1.338-10.5c3.863-.277 7.092 1.765 9.373 4.036");
}

</style>
