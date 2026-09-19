<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p-0bs0i3k"/><path class="y9px6kbhy"/><path class="hmp6-u_2v"/><ellipse class="u5lrlnhcn"/><ellipse class="xo1k63b9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stick-with-it" /></template>
<style>
.hmp6-u_2v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.846 14.493a5.3 5.3 0 0 1 1.158 3.308h0a5.303 5.303 0 0 1-5.303 5.304h0a5.303 5.303 0 0 1-5.303-5.304h0c0-2.64 1.943-4.88 4.557-5.25M36.23 22.26c.285.662.432 1.375.432 2.095h0a5.303 5.303 0 0 1-5.303 5.304h0a5.303 5.303 0 0 1-5.304-5.304h0a5.303 5.303 0 0 1 5.025-5.296");
}

.p-0bs0i3k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.732 26.527l2.768-1.112M4.5 39.43l5.856-2.062m.344-.125c2.045 1.77 7.654 2.746 18.809 2.746c2.952-.534 4.527-2.259 6.209-6.155c1.77-5.316 5.097-3.2 5.012-7.517M10.7 37.243c-2.092-1.405-3.476-6.908-3.476-11.534c0-9.705 6.036-17.698 15.742-17.698s17.806 7.172 17.806 16.878h0c0 .606.009.765-.042 1.428M10.6 23.381l18.3 12.702");
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
