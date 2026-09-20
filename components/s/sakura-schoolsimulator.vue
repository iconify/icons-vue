<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mkw594bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sakura-schoolsimulator" /></template>
<style>
.mkw594bts {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.483 15.683c2.352-5.394 0-10.183 0-10.183c-25.843 7.494-22.482 27.02-15.224 37c23.894-.302 30.447-14.316 24.802-31.354c-6.251 1.613-9.578 4.537-9.578 4.537");
}

</style>
