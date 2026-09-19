<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="qp6mnsbnm"/><circle class="c6_ejtbyy"/><circle class="uqx3fsb9e"/><circle class="o19h_6b2u"/><path class="gqa5wlbiy"/><path class="u-zoydbld"/><path class="doy40cb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:petco" /></template>
<style>
.c6_ejtbyy {
  cx: 30.043px;
  cy: 24.664px;
  r: 0.75px;
  fill: currentColor;
}

.doy40cb9b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.673 27.74c-.332 1.614-1.36 2.777-2.572 2.777s-2.239-1.163-2.571-2.777c.616-.274 1.545-.44 2.571-.44s1.956.166 2.572.44m-16.046-1.374c-.166.807-.68 1.389-1.285 1.389s-1.12-.582-1.286-1.389c.308-.137.772-.22 1.286-.22s.977.083 1.285.22m3.792.585l3.374-.721m-3.566 2.099l2.626.725M7.609 26.951l-3.374-.721m3.566 2.099l-2.626.725m7.167-1.299c0 1.616 2.074 2.589 3.116.711m-3.116-.643c0 1.615-2.076 2.589-3.117.71M24.53 35.07c1.689 1.765 3.775 1.336 5.045-.053");
}

.gqa5wlbiy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.342 20.896c-1.137 0-1.522.206-1.522.206s-.781-3.907-3.125-3.907S3.5 21.555 3.5 24.803s3.33 9.006 8.841 9.006s8.842-5.757 8.842-9.006s-1.85-7.608-4.195-7.608s-3.125 3.907-3.125 3.907s-.386-.206-1.522-.206");
}

.o19h_6b2u {
  cx: 15.323px;
  cy: 24.664px;
  r: 0.75px;
  fill: currentColor;
}

.qp6mnsbnm {
  cx: 24.08px;
  cy: 24.664px;
  r: 0.75px;
  fill: currentColor;
}

.u-zoydbld {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.183 24.803c0 3.29-2.157 4.64-2.157 7.026s2.075 3.625 3.925 3.625s4.154-1.686 4.154-4.935c0 3.249 2.303 4.935 4.153 4.935s3.926-1.24 3.926-3.625s-2.157-3.736-2.157-7.026s2.467-7.608 4.359-7.608c1.974 0 2.261 3.701 4.194 3.701c1.152 0 2.92-1.562 2.92-4.359s-1.521-4.77-5.058-4.77s-5.798 1.11-7.526 3.783c0 0-1.398-1.315-4.811-1.315s-4.811 1.315-4.811 1.315c-1.728-2.673-3.99-3.783-7.526-3.783s-5.058 1.974-5.058 4.77s2.632 4.36 2.632 4.36");
}

.uqx3fsb9e {
  cx: 9.36px;
  cy: 24.664px;
  r: 0.75px;
  fill: currentColor;
}

</style>
