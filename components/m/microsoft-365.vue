<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sk8rddbvf"/><path class="hhz66acdh"/><path class="ykw7zbbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:microsoft-365" /></template>
<style>
.hhz66acdh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.166 19.275v4.45a8.6 8.6 0 0 1-4.508 7.564l-11.466 6.202a8.6 8.6 0 0 1-7.435.358q.33.222.687.414l11.465 6.202a8.6 8.6 0 0 0 8.182 0l11.465-6.202a8.6 8.6 0 0 0 4.508-7.563");
}

.sk8rddbvf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.507 3.241L8.443 9.74a8.6 8.6 0 0 0-4.508 7.563V30.7a8.6 8.6 0 0 0 4.508 7.564m15.668-5.597l-2.826-1.557a8.6 8.6 0 0 1-4.45-7.532v-4.072");
}

.ykw7zbbec {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.557 9.739L28.092 3.536a8.6 8.6 0 0 0-7.585-.295a8.6 8.6 0 0 0-3.673 7.048v8.986l3.288-1.661a8.6 8.6 0 0 1 7.756 0l11.465 5.793a8.6 8.6 0 0 1 4.72 7.484l.001-.191V17.302a8.6 8.6 0 0 0-4.507-7.563");
}

</style>
