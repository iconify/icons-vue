<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="fd-ig-g0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tradera" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fd-ig-g0z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.305 22.885l1.184-5.167m7.206 4.37l-7.798-1.787m20.425 14.144v8h-2.619c-1.48 0-2.681-1.203-2.681-2.687s1.2-2.686 2.681-2.686h2.619m-2.619-.001l-2.619-2.624m10.359-21.376l-3.184-1.557m-1.952 1.996l5.895-6.023l-1.134 8.351m2.775 3.582l7.836-1.612l.363 1.763a3.5 3.5 0 0 1-2.723 4.134l-.98.201a3.5 3.5 0 0 1-4.133-2.723zm3 11.63l-1.623 2.041m-3.998-1.396l2.49-3.131l6.261 4.979l-2.489 3.131M16.738 16.082l-4.111-6.863l2.246-1.346a2.684 2.684 0 0 1 3.68.927a2.684 2.684 0 0 1-.918 3.683l-2.247 1.346m2.247-1.346l3.595.905m-9.208 16.911l2.018 2.914m2.678-.788l-8.085 2.377l5.067-6.734");
}

</style>
