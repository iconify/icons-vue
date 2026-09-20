<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xkbs35b_m"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:umoney" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.xkbs35b_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.795 22.571c.45-2.426 2.392-4.392 4.346-4.392c1.947 0 3.164 1.966 2.714 4.392l-1.346 7.25m-12.774-7.25c.453-2.426 2.396-4.392 4.346-4.392c1.947 0 3.164 1.966 2.714 4.392l-1.342 7.25M14.491 18.18l-1.346 7.249c-.45 2.422.767 4.391 2.718 4.391c1.95 0 3.893-1.965 4.346-4.391l1.342-7.25");
}

</style>
