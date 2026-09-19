<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><path class="yzc9wx7vo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:t-connect" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.yzc9wx7vo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.079 19.713C31.8 18 26.996 19.48 26.996 24s4.805 5.999 8.083 4.287M11.65 19.36h9.709m-4.854.129v9.49m6.865-8.491c-.847.615-1.855 2.093-1.855 3.722s1.008 3.107 1.855 3.722m1.763-6.342c-.5.433-1.097 1.473-1.097 2.62s.597 2.187 1.097 2.62");
}

</style>
