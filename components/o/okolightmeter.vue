<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lfodxkrun"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:okolightmeter" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.lfodxkrun {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M24 14.36a9.62 9.62 0 0 1 6.816 2.824c1.81 1.806 2.825 4.26 2.825 6.816s-1.014 5.01-2.825 6.816c-1.806 1.81-4.26 2.825-6.816 2.825s-5.01-1.014-6.816-2.825c-1.81-1.806-2.825-4.26-2.825-6.816s1.014-5.01 2.825-6.816A9.62 9.62 0 0 1 24 14.36Zm0 0");
}

</style>
