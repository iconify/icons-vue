<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vipz4-zul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:umassfive" /></template>
<style>
.vipz4-zul {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m43.5 20.898l-12.664-2.826l-3.48-11.856l-6.963 9.485l-15.893.353l12.966 9.435L5.913 38.656l16.296-7.063l9.132 10.191l-1.917-15.791z");
}

</style>
