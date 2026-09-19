<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sy_46skaa"/><path class="kg4hgtb4t"/><path class="gopuittut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:newegg" /></template>
<style>
.gopuittut {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.808 13.328C16.153 9.184 6.642 16.941 4.856 23.445C2.95 30.392 8.906 38.849 17.8 34.772");
}

.kg4hgtb4t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.783 13.327C25.128 9.183 15.617 16.94 13.83 23.444c-1.907 6.947 4.05 15.405 12.944 11.328");
}

.sy_46skaa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.856 34.774c10.161-5.227 9.134-21.085 3.071-22.43c-5.567-1.236-14.056 4.205-16.014 11.1c-1.968 6.931 4.05 15.406 12.943 11.33");
}

</style>
