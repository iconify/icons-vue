<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sxdk1aczy"/><path class="kngrf7b-m"/><path class="z6_9lbbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sevenly" /></template>
<style>
.kngrf7b-m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.861 13.864c-3.77 4.034-6.378 11.45-5.562 21.636h7.79c.47-8.32-.548-17.168 6.525-20.951V7.5m.388 15l-1.682 12h6m6.267 0l-3.14-12");
}

.sxdk1aczy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 7.5v6.413l11.361-.05C19.05 11.036 22.64 9.11 25.614 7.5z");
}

.z6_9lbbkl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.5 22.5l-7.983 16.199c-.532 1.08-1.653 1.801-2.797 1.801H11.299");
}

</style>
