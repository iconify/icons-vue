<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8ozsw7jd"/><circle class="n1xy6nh9u"/><path class="apuaovb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-cameraswitch" /></template>
<style>
.apuaovb1t {
  fill: currentColor;
  d: path("M8.57.52L13.05 5l1.41-1.41l-1.54-1.54C17.7 2.46 21.53 6.24 22 11h2C23.36 3.3 15.79-1.67 8.57.52m.97 19.89l1.54 1.54C6.3 21.54 2.47 17.76 2 13H0c.64 7.7 8.21 12.67 15.43 10.48L10.95 19z");
}

.n1xy6nh9u {
  cx: 12px;
  cy: 12px;
  r: 2px;
  fill: currentColor;
}

.v8ozsw7jd {
  fill: currentColor;
  d: path("M16 7h-1l-1-1h-4L9 7H8c-1.1 0-2 .9-2 2v6c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V9c0-1.1-.9-2-2-2m0 8H8V9h1.83l1-1h2.34l1 1H16z");
}

</style>
