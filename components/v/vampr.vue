<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q4depivew"/><path class="iqavru3fn"/><path class="nbiy5kbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vampr" /></template>
<style>
.iqavru3fn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.256 12.718l18.986.08c4.402.034 5.485 3.774 3.889 6.374L30.563 35.58c-2.235 3.797-6.009 2.862-7.457.17l-9.43-16.477c-2.167-3.831.524-6.648 3.58-6.556");
}

.nbiy5kbyl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.28 13.151l11.483 6.545c2.657 1.54 2.03 4.174.171 5.2l-11.414 6.67c-2.657 1.529-4.63-.33-4.584-2.45l-.068-13.217c0-3.067 2.6-3.854 4.413-2.748");
}

.q4depivew {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.084 14.839l23.832-8.815c5.542-2.018 8.655 2.167 7.857 6.17l-4.277 25.051c-1.026 5.804-6.203 6.409-9.27 3.718L8.67 24.725c-4.516-3.786-2.452-8.575 1.414-9.886");
}

</style>
