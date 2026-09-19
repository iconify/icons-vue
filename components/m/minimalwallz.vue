<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="breb99b4o"/><path class="b1ccbcb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:minimalwallz" /></template>
<style>
.b1ccbcb6g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.742 30.825l6.565 6.565l15.484-15.484");
}

.breb99b4o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.209 40.359L24 24.567L8.209 8.776zm22.356-9.227l9.226 9.227V8.776L24 24.567");
}

</style>
