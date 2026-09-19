<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gqe9355-s"/><path class="rxszi2kuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:memo-game" /></template>
<style>
.gqe9355-s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5h10v10h-10zm13.5 0h10v10H19zm13.5 0h10v10h-10zM5.5 19h10v10h-10zM19 19h10v10H19zm13.5 0h10v10h-10zm-27 13.5h10v10h-10zm13.5 0h10v10H19zm13.5 0h10v10h-10z");
}

.rxszi2kuv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 22h4v4h-4zm27-13.5h4v4h-4z");
}

</style>
