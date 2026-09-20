<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t7m7i9arm"/><path class="y9px6kbhy"/><path class="l2lvdclqh"/><ellipse class="u5lrlnhcn"/><ellipse class="xo1k63b9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stick-with-it" /></template>
<style>
.l2lvdclqh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.846 14.493a5.303 5.303 0 0 1-4.145 8.611a5.303 5.303 0 0 1-.746-10.554m17.275 9.71a5.303 5.303 0 0 1-4.872 7.399a5.303 5.303 0 0 1-.279-10.6");
}

.t7m7i9arm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.732 26.527l2.768-1.112M4.5 39.43l5.856-2.062m.344-.125c2.045 1.77 7.654 2.746 18.809 2.746c2.952-.534 4.527-2.259 6.209-6.155c1.77-5.316 5.097-3.2 5.012-7.517M10.7 37.243c-2.092-1.405-3.476-6.908-3.476-11.534c0-9.705 6.036-17.698 15.742-17.698s17.806 7.172 17.806 16.878c0 .606.009.765-.042 1.428M10.6 23.381l18.3 12.702");
}

.u5lrlnhcn {
  cx: 31.441px;
  cy: 24.294px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.114px;
  ry: 3px;
}

.xo1k63b9l {
  cx: 19.814px;
  cy: 17.586px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.016px;
  ry: 3px;
}

.y9px6kbhy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.126 11.793c.082.103.861 1.087 3.691.697l5.147 3.404m11.566 7.485l-3.302-3.425c-.472.082-1.21.636-4.84-2.05");
}

</style>
