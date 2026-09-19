<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f4sko53ft"/><path class="sny7n3bte"/><path class="yzm6tvk8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:microsoft-viva-engage" /></template>
<style>
.f4sko53ft {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.002 30.384c0 7.794 5.04 12.116 11.01 12.116a8.832 8.832 0 1 0 0-17.664c-5.715 0-11.01-4.32-11.01-9.954z");
}

.sny7n3bte {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.936 24.82a9.149 9.149 0 1 0-16.115-.048");
}

.yzm6tvk8e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.002 14.882c0-5.57 3.537-9.382 8.832-9.382s7.045 3.348 8.552 5.825m.613 16.943a8.82 8.82 0 0 1 6.99-3.432c5.714 0 11.009-4.32 11.009-9.954v15.502c0 7.794-5.04 12.116-11.01 12.116A8.82 8.82 0 0 1 24 39.068m17.998-24.186c0-5.57-3.537-9.382-8.831-9.382c-5.295 0-7.046 3.348-8.553 5.825");
}

</style>
