<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a60zjrbaf"/><path class="ubmeigbii"/><path class="gz-5ms5ko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:simplytranslate-alt" /></template>
<style>
.a60zjrbaf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.117 19.217l3.122-9.25m0 0l3.006 9.25m-1.04-3.122h-4.048m-9.951 22.243a11.03 11.03 0 0 0 9.25 4.162h5.55a9.25 9.25 0 0 0 0-18.5h-6.012a9.25 9.25 0 0 1 0-18.5h5.55c4.162 0 6.937.925 9.25 4.163");
}

.gz-5ms5ko {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.585 38.298c3.602-1.143 5.416-4.44 6.261-7.827");
}

.ubmeigbii {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.794 7.35v2.313H33.48M14.519 38.338h-2.313v2.312m7.524-10.18h8.54M24 29.048v1.423m-2.135 2.134a14 14 0 0 0 4.981 5.693");
}

</style>
