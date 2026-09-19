<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="va1si9bnw"/><path class="ncgopslcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:swiggy" /></template>
<style>
.ncgopslcz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.199 18.479H25.955v-5.924M14.502 29.442h10.122v4.554");
}

.va1si9bnw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.223 17.723a13.223 13.223 0 0 0-26.446 0C10.777 27.773 24 43.5 24 43.5s13.223-15.727 13.223-25.777");
}

</style>
