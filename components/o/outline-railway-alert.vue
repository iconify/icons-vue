<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="r1y0urzis"/><path class="ip9o00bca"/><path class="w9pxaxgbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-railway-alert" /></template>
<style>
.ip9o00bca {
  fill: currentColor;
  d: path("M4 11V8h7.29C11.1 7.37 11 6.7 11 6H4.43c.9-.77 3.28-1.08 6.65-.98c.1-.7.3-1.37.59-1.99C2.97 2.67 2 5.02 2 7v9.5C2 18.43 3.57 20 5.5 20L4 21v1h12v-1l-1.5-1c1.93 0 3.5-1.57 3.5-3.5V13c-1.91 0-3.63-.76-4.89-2zm12 5.5c0 .83-.67 1.5-1.5 1.5h-9c-.83 0-1.5-.67-1.5-1.5V13h12z");
}

.r1y0urzis {
  cx: 10px;
  cy: 15.5px;
  r: 1.5px;
  fill: currentColor;
}

.w9pxaxgbc {
  fill: currentColor;
  d: path("M18 1c-2.76 0-5 2.24-5 5s2.24 5 5 5s5-2.24 5-5s-2.24-5-5-5m.5 8h-1V8h1zm0-2h-1V3h1z");
}

</style>
