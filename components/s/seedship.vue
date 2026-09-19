<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t1m1qf2iw"/><circle class="bu1v4ub7w"/><path class="zhhr7nbpq"/><circle class="spk6i4bot"/><circle class="dzrca8bys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:seedship" /></template>
<style>
.bu1v4ub7w {
  cx: 23.147px;
  cy: 17.721px;
  r: 2.491px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.dzrca8bys {
  cx: 29.654px;
  cy: 15.349px;
  r: 0.75px;
  fill: currentColor;
}

.spk6i4bot {
  cx: 28.056px;
  cy: 17.333px;
  r: 0.75px;
  fill: currentColor;
}

.t1m1qf2iw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.512 12.861H31.85v28.601H14.512zm-4.471 28.601h26.28M31.85 23.803c2.148 1.34 9.068-1.644 11.65-9.01M31.85 32.387c2.36 2.131 5.537 5.18 11.65-7.12m-28.988-5.603C11.14 19.664 4.5 12.052 4.5 6.538m6.641.963h5.608m2.32-.01h8.237m2.389.01h5.609");
}

.zhhr7nbpq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.483 26.055a4.336 4.336 0 1 0-8.672 0v3.407h1.688l.379 8.235h4.752l.436-8.157h1.417ZM16.75 12.861c0 2.765 1.54 6.01 4.012 5.57");
}

</style>
