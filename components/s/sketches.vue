<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="trentc0yp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sketches" /></template>
<style>
.trentc0yp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.25 4.5v5.488h15.5V4.5m0 5.488l-1.468 16.148H17.719L16.25 9.988m11.833 16.148l-1.485 2.803h-5.195l-1.485-2.803m6.68 2.804v5.432h-5.195v-5.433m3.606 5.433v2H22.99v-2m1.01 2V43.5M22.45 9.988l.24 13.235m2.86-13.235l-.24 13.235M19.35 9.988l.722 13.235M28.65 9.988l-.722 13.235");
}

</style>
