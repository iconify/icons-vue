<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="io1xjdb7r"/><ellipse class="kz74wjbft"/><path class="hi6_l9b7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:malclient" /></template>
<style>
.hi6_l9b7t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.844 35.074a32.2 32.2 0 0 0 10.191-3.129m-8.962-3.129a1.244 1.244 0 0 1 .484 2.262a1.26 1.26 0 0 1-1.397-.008a1.235 1.235 0 0 1-.51-1.296m-1.818-9.562a1.254 1.254 0 1 1-1.54 1.41m-6.465-2.83c-1.2.369-9.404 5.302-9.404 5.302l9.943 6.407l-4.17-6.387z");
}

.io1xjdb7r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.944 20.212c1.617-.594 3.314.464 4.068 2.536a6.25 6.25 0 0 1-.96 6.057m-1.543.905c-1.477.397-2.974-.544-3.733-2.347a6.49 6.49 0 0 1 .361-5.665M43.5 18.87a121.8 121.8 0 0 0-39-5.978c14.304.023 24.25 3.04 35.312 11.007");
}

.kz74wjbft {
  cx: 24.95px;
  cy: 25.687px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6.627px;
  ry: 9.42px;
}

</style>
