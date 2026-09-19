<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t-gb51bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:splid" /></template>
<style>
.t-gb51bpp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.077 6.513A11.594 11.594 0 1 0 21.02 25.677m-7.097 15.81A11.594 11.594 0 1 0 26.98 22.323");
}

</style>
