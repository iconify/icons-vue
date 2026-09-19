<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bgqpep3us"/><path class="li27a4bul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:parcel" /></template>
<style>
.bgqpep3us {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.29 14.914L24 26.328V44.5L7.29 33.086zm33.421 0L24 26.328V44.5l16.711-11.414zm0 0L24 3.5L7.29 14.914");
}

.li27a4bul {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.002 10.332L17.291 21.746V28.2l-3.984-2.785v-6.39L30.017 7.61");
}

</style>
