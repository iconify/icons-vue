<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rl53icbth"/><path class="pt3rbpbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:whm" /></template>
<style>
.pt3rbpbhz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.25 37.351V26.67L24 21.33l-9.25 5.34v10.681L24 42.692z");
}

.rl53icbth {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 21.33V10.649l-9.25-5.341l-9.25 5.341V21.33l9.25 5.34zm18.5 0V10.649l-9.25-5.341L24 10.649V21.33l9.25 5.34z");
}

</style>
