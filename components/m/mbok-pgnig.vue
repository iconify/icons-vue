<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="at6eacc6y"/><path class="f-g4phbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mbok-pgnig" /></template>
<style>
.at6eacc6y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.924 5.5c-5.449 14.659-28.756 11.373-28.756 25.167c0 11.833 20.28 7.654 23.524 1.686c-5.06 14.054-30.616 13.146-30.616-.476c0-16.82 26.205-15.956 35.848-26.377");
}

.f-g4phbxu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.205 24c-6.14 6.407-11.891 7.418-18.55 7.029c.907 4.67 14.183 4.639 18.55-7.029m-17.853 2.85c3.972-6.156 14.44-4.93 19.929-12.312c-2.308 10.05-14.567 12.053-19.93 12.312");
}

</style>
