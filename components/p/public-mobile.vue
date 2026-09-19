<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kmnmflb_i"/><path class="wgs2y-eft"/><path class="h65wnbnde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:public-mobile" /></template>
<style>
.h65wnbnde {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.663 29.541l2.015-10.075h3.275c1.889 0 2.896.503 2.896 2.392s-2.015 3.401-3.904 3.401h-3.426m1.159-5.793H21.67m0 10.075h-2.015");
}

.kmnmflb_i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.566 11.08l9.387 2.516c.902.241 1.333 1.554.964 2.933l-5.182 19.34c-.37 1.378-1.4 2.3-2.301 2.058l-9.387-2.515c-.902-.242-1.334-1.555-.964-2.933l5.182-19.34c.37-1.379 1.4-2.3 2.301-2.059");
}

.wgs2y-eft {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.388 30.909l-3.875-1.039c-.905-.242-1.334-1.55-.964-2.933l5.182-19.34c.37-1.383 1.397-2.3 2.301-2.058l9.388 2.515c.904.242 1.334 1.55.963 2.933l-.378 1.414m4.756 4.709l3.726 1.02c.903.247 1.335 1.55.964 2.933l-5.182 19.34c-.37 1.383-1.397 2.3-2.301 2.058l-9.387-2.515c-.905-.242-1.335-1.55-.964-2.933l.155-.58");
}

</style>
