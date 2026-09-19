<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tmwho_b5r"/><path class="b_6qajb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:openvpnconnect" /></template>
<style>
.b_6qajb2g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5a21.62 21.62 0 0 0-10.87 40.24l3.32-10.18a11.42 11.42 0 0 1-.83-16a11.22 11.22 0 0 1 15.93-.84a11.42 11.42 0 0 1 .83 16a9 9 0 0 1-.83.84l3.32 10.18a21.68 21.68 0 0 0 7.7-29.53A21.41 21.41 0 0 0 24 2.5");
}

.tmwho_b5r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.82 24.09a6.82 6.82 0 1 0-9.92 6.17l-2.73 14.62a21.6 21.6 0 0 0 5.83.61a21.3 21.3 0 0 0 5.84-.61l-2.72-14.62a6.88 6.88 0 0 0 3.7-6.17");
}

</style>
