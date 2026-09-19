<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jqgmvmbjj"/><path class="awxdy-bnm"/><path class="eo01nobib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-honor" /></template>
<style>
.awxdy-bnm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.461 37.464L41.326 23.09c1.181-1.07 1.73-2.38.403-4.13l-6.29-8.289c-.555-.731-.953-.804-2.696-.807l-18.375-.031c-.865-.002-1.376.324-1.86.962l-6.413 8.476c-1.03 1.36-.594 2.543.31 3.384L22.3 37.465c.866.806 1.991 1.06 3.161 0Z");
}

.eo01nobib {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.755 10.073L23.81 38.166l-7.193-20.834m-3.105-7.358l1.669 4.23");
}

.jqgmvmbjj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.63 19.449l-.986-2.117l-2.113-.988l2.113-.988l.986-2.117l.986 2.117l2.113.988l-2.113.988z");
}

</style>
