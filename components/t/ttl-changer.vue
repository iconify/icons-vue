<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q88-vukto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ttl-changer" /></template>
<style>
.q88-vukto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.925 13.575L4.5 24l10.425 10.425m18.15-20.85L43.5 24L33.075 34.425M15.492 22.298h3.403v3.404h-3.403zm13.613 0h3.403v3.404h-3.403zm-6.807 0h3.404v3.404h-3.404z");
}

</style>
