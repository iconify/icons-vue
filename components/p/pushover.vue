<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p7nnaibpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pushover" /></template>
<style>
.p7nnaibpb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.753 22.91C10.028 18.639 14.93 5.283 28.775 5.283c6.923 0 9.649 3.051 9.649 8.608c0 5.735-6.479 13.467-19.746 13.467m7.516-17.532L11.421 44.283");
}

</style>
