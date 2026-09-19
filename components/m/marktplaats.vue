<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iwembvn_s"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:marktplaats" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.iwembvn_s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.005 35.5h15.99m-10.441-23a112 112 0 0 1 8.908 9.456s-6.864 7.885-8.616 9.09");
}

</style>
