<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="axyt1xibx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:simpl" /></template>
<style>
.axyt1xibx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.924 14.324c6.674 6.675 6.674 17.496 0 24.17s-17.496 6.675-24.17 0m2.323-4.818c-6.675-6.675-6.675-17.496 0-24.17s17.495-6.675 24.17 0");
}

</style>
