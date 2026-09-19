<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="zx5g_3blx"/><circle class="sysj6k5rp"/><circle class="njeh5bb6p"/><circle class="ifqhv4b6g"/><path class="aaamsbb8a"/><path class="d-xq5jg1w"/><ellipse class="i75zsabrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:traffic-rider" /></template>
<style>
.aaamsbb8a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.809 28.422l5.542-6.219m21.641 5.623l-5.975-14.215h-3.398M7.586 21.383l12.841 6.443m3.251-1.756L8.582 18.102l3.594-.937l8.994 2.152");
}

.d-xq5jg1w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.909 19.089s1.21.576 1.913 2.06h5.39l-1.123-4.033h-6.932c-1.738 0-3.184 1.621-3.32 3.602h5.753m.34 6.924l5.282-6.493m-1.318 4.491c.098-1.65 3.535-7.167 9.686-4.667");
}

.i75zsabrt {
  cx: 23.678px;
  cy: 27.826px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.252px;
  ry: 1.756px;
}

.ifqhv4b6g {
  cx: 9.382px;
  cy: 29.507px;
  r: 1.797px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.njeh5bb6p {
  cx: 9.382px;
  cy: 29.507px;
  r: 4.882px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sysj6k5rp {
  cx: 38.618px;
  cy: 29.507px;
  r: 1.797px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zx5g_3blx {
  cx: 38.618px;
  cy: 29.507px;
  r: 4.882px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
