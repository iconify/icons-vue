<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs5mdjbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:thermometer" /></template>
<style>
.vs5mdjbhu {
  fill: currentColor;
  d: path("M12 21q-2.075 0-3.537-1.463T7 16q0-1.2.525-2.238T9 12V6q0-1.25.875-2.125T12 3t2.125.875T15 6v6q.95.725 1.475 1.763T17 16q0 2.075-1.463 3.538T12 21m-1-11h2V6q0-.425-.288-.712T12 5t-.712.288T11 6z");
}

</style>
