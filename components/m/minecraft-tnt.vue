<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jt3nzbkaa"/><path class="tjy1rabhv"/><path class="g1vv27uhj"/><path class="yqdg3taaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:minecraft-tnt" /></template>
<style>
.g1vv27uhj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.243 34.467L24 45V24.066l18.243-10.533zM24 29.994L5.757 19.461m0 9.078L24 39.072M8.651 23.507l2.913 1.682m-1.457 3.456v-4.297m7.824 4.517l2.912 1.681m-1.456 3.456v-4.296m-6.096.777v-4.297l2.912 5.994v-4.297m26.04-8.422L24 29.994m0 9.078l18.243-10.533m-15.348 2.159l2.912-1.682m-1.456 5.138v-4.297m7.823-4.517l2.913-1.681m-1.456 5.137v-4.297");
}

.jt3nzbkaa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 45L5.756 34.467V13.533L24 24.066z");
}

.tjy1rabhv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 24.066L5.756 13.533L24 3l18.243 10.533z");
}

.yqdg3taaf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.535 32.316v-4.297l2.912 2.631v-4.297M20.768 15.399l6.464-3.732m-6.484-.012l6.504 3.756");
}

</style>
