<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kapikvtay"/><path class="g9rjzb04m"/><path class="le5nyfb5b"/><path class="uh--57jig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:xmpp" /></template>
<style>
.g9rjzb04m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.5 11.5c-1.5 5.378 5.5 24.75 24 27");
}

.kapikvtay {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 9.5l12 4c0 9 5.5 17.5 18 25C19 36 8 26.5 5.5 9.5");
}

.le5nyfb5b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.892 33.148C35.753 28.288 40.889 20.45 42.5 9.5l-12 4c0 5.492-2.048 10.798-6.485 15.803m-4.007 3.89C17.861 35.01 15.364 36.78 12.5 38.5c4.172-.633 7.993-1.712 11.414-3.248");
}

.uh--57jig {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.5 11.5c1.018 3.65-1.88 13.75-9.634 20.564m-3.403 2.553C20.391 36.563 16.75 37.983 12.5 38.5");
}

</style>
