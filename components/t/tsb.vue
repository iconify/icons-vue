<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dtz5973zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tsb" /></template>
<style>
.dtz5973zc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 36.55c7.012-9.3 13.742-10.531 20.5-12.55M24 36.55C16.988 27.25 10.258 26.019 3.5 24M24 11.45c7.012 9.3 13.742 10.531 20.5 12.55M24 11.45C16.988 20.75 10.258 21.981 3.5 24m10.74 0h19.52");
}

</style>
