<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b-3ppof3d"/><path class="wwkjjcc-w"/><ellipse class="gqns12bia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:private-dns-quick-toggle" /></template>
<style>
.b-3ppof3d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.281 36.889h26.705c14.496 0 12.071-21.813-2.467-16.976c0-12.113-21.813-12.113-21.813 2.426C-.42 19.913-.42 36.889 9.28 36.889");
}

.gqns12bia {
  cx: 23.437px;
  cy: 28.635px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.432px;
  ry: 1.447px;
}

.wwkjjcc-w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.02 23.908V21.4c0-2.557-2.051-4.63-4.583-4.63s-4.583 2.073-4.583 4.63v2.508m-2.291 0h13.75v9.454h-13.75z");
}

</style>
