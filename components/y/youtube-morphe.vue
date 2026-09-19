<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qo8o0s0zt"/><path class="s8ihr2b8q"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:youtube-morphe" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qo8o0s0zt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11 19.769v12.694c.075 1.586 1.428 2.87 3.006 2.87s2.93-1.284 3.005-2.87V22.262m13.978 0v10.2c.074 1.587 1.427 2.871 3.005 2.871s2.93-1.284 3.006-2.87V16.217");
}

.s8ihr2b8q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.306 12.667c-2.555 0-3.306 1.888-3.306 3.021v4.08c2.255-2.494 5.636 2.041 6.011 2.494c2.105 2.418 3.307 6.573 6.989 6.725c3.607-.152 5.035-4.232 6.989-6.725c0 0 3.38-5.59 6.011-6.045c0-2.115-.827-3.55-3.306-3.55c-2.556 0-4.359 3.777-5.637 5.439c-1.276 1.663-1.877 3.476-4.057 3.476s-2.856-1.89-4.057-3.476c-1.278-1.662-3.081-5.44-5.637-5.44Z");
}

</style>
