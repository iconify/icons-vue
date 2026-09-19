<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="encyp0bgk"/><ellipse class="pwl14wbdp"/><path class="ot4q39b_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nasa-imagery-fetcher" /></template>
<style>
.encyp0bgk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.197 20.326a1.645 1.645 0 1 1-1.509-2.922");
}

.ot4q39b_w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.424 17.571L31.378 5.926M14.075 20.382l20.532-7.949m-9.976 3.863v29.206m0-29.206l6.754 25.109m-6.754-25.109l-6.754 25.109M37.28 24.334l-2.552-.842l-2.078 1.7l.016-2.678l-2.265-1.443l2.562-.812l.678-2.59l1.567 2.175l2.684-.159l-1.593 2.157ZM13.236 2.5a4.036 4.036 0 0 0 .931 7.968h.001a4.055 4.055 0 0 0 3.886-2.898a3.509 3.509 0 0 1-4.818-5.07");
}

.pwl14wbdp {
  cx: 33.269px;
  cy: 9.044px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.656px;
  ry: 3.642px;
}

</style>
