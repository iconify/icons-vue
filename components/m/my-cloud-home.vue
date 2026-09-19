<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sixzphbwl"/><path class="xxg-48buf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-cloud-home" /></template>
<style>
.sixzphbwl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 16.32l18.542-9.607L42.5 16.261v20.946c-.009 1.987-1.646 3.893-4.104 4.08H9.849c-2.888-.327-4.228-2.144-4.264-4.108z");
}

.xxg-48buf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.401 33.407h12.884c8.07-2.861 5.762-12.965-2.3-13.178c-4.89-3.019-8.575-2.577-11.308 1.979c-5.958 3.59-4.442 9.898.724 11.199");
}

</style>
