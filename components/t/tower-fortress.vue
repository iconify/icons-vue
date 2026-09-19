<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y3vvqhbcb"/><path class="fw_qerb5b"/><path class="y43z9pboo"/><path class="nud8h-bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tower-fortress" /></template>
<style>
.fw_qerb5b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.653 23.584c0-7.85 5.893-14.325 13.466-15.28m3.705 0c7.602.913 13.465 7.39 13.465 15.279v6.761c0 2.158-.556 3.992-.556 3.992l-6.552 6.6l-3.046 1.756c-1.031.598-.885.415-3.935.415V39.62h3.744l6.341-6.341v-9.206c0-1.72-.885-.565-3.4.248s-5.271 1.05-7.936 1.05");
}

.nud8h-bik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.726 15.753A7.306 7.306 0 0 0 3.6 21.855a7.306 7.306 0 0 0 4.747 8.089m14.412 11.498h2.52M35.364 24.92L22.76 40.583m.38-15.185l-2.616 2.454v7.936l-1.767 3.6m16.607-10.074l1.987-1.614v-4.937c0-2.655-1.557-2.283-3.42-1.5s-3.284 1.337-3.37 1.299s-1.117-2.091-1.251-2.14c-.13-.05-3.056.487-3.486.517m-13.188 8.375L10.649 27.7v-4.937c0-2.655 1.557-2.283 3.42-1.5s3.284 1.337 3.37 1.299s1.117-2.091 1.251-2.14c.13-.05 3.056.487 3.486.517");
}

.y3vvqhbcb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.815 22.533V4.866h-3.591v17.667c0 .706 3.59.706 3.59 0");
}

.y43z9pboo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.274 15.753a7.306 7.306 0 0 1 7.125 6.102a7.306 7.306 0 0 1-4.747 8.089m-30.999-6.36v6.761c0 2.158.557 3.992.557 3.992l6.551 6.599l3.047 1.757c1.031.598.885.415 3.934.415v-3.486H19l-6.341-6.341v-9.206c0-1.72.885-.566 3.4.248s5.27 1.05 7.935 1.05");
}

</style>
