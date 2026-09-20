<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="t04ev4s5z"/><path class="vrczho25c"/><path class="l-v0y7uhl"/><path class="nak4k_brd"/><circle class="tk2mivs1j"/><path class="orhvb-bqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:military-medal" /></template>
<style>
.l-v0y7uhl {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M14 0v18.111L16.429 20h3.142L22 18.111V0z");
}

.nak4k_brd {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M21.902 21.02A1.5 1.5 0 0 0 22 20.5a1.5 1.5 0 0 0-1.5-1.5h-5a1.5 1.5 0 0 0-1.5 1.5c0 .183.038.357.098.52A7.99 7.99 0 0 0 10 28a8 8 0 1 0 16 0c0-3-1.654-5.611-4.098-6.98");
}

.orhvb-bqc {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M20.731 32.36a.6.6 0 0 1-.339-.109L18 30.535l-2.393 1.716a.58.58 0 0 1-.892-.647l.892-2.88l-2.371-1.671a.582.582 0 0 1 .341-1.049L16.514 26l.935-2.809a.58.58 0 0 1 1.102 0L19.47 26l2.952.004a.58.58 0 0 1 .341 1.049l-2.371 1.671l.892 2.88a.58.58 0 0 1-.553.756");
}

.t04ev4s5z {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M25 0H11a2 2 0 0 0-2 2v11s0 1 1 2l6.429 5h3.142L26 15c1-1 1-2 1-2V2a2 2 0 0 0-2-2");
}

.tk2mivs1j {
  cx: 18px;
  cy: 28px;
  r: 6px;
  fill: var(--svg-color--ffd983, #ffd983);
}

.vrczho25c {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M12 0v16.555L16.429 20h3.142L24 16.555V0z");
}

</style>
