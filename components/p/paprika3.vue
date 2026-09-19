<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wyxtkdbez"/><path class="fidw94vsy"/><ellipse class="xd54hgj8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:paprika3" /></template>
<style>
.fidw94vsy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.042 14.967l.066 19.016c.047 6.44 3.439 8.197 7.857 8.517h19.346c6.476-.375 8.296-3.544 8.65-7.593V14.77");
}

.wyxtkdbez {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.714 28.547c.722-.516 1.933-.038 3.401.961a60.4 60.4 0 0 1 9.083-.284a10.4 10.4 0 0 0 3.156-1.246c1.698-1.348 2.324-2.885 5.857-3.81c.966-.022 1.667-.046 2.945 3.738a6.92 6.92 0 0 1-.631 4.557c-1.16 1.505-3.234 2.853-9.854 3.418c-3.338-.139-6.985-.121-9.082-.89c.393.279-6.621-4.268-4.875-6.444m24.443-.641c2.466-.452 3.295-1.743 3.05-3.24M23.97 20.333H12.565c-5.035 0-6.314-3.618-6.523-5.366h0C5.958 11.183 7.804 5.5 14.03 5.5h19.876c6.227 0 8.073 5.683 7.99 9.467h0c-.21 1.748-1.489 5.366-6.524 5.366Z");
}

.xd54hgj8m {
  cx: 24.001px;
  cy: 12.755px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.791px;
  ry: 4.919px;
}

</style>
