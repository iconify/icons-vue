<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="l-3swtbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tatilbudur" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l-3swtbzj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.555 14.113v13.765a2.88 2.88 0 0 0 2.877 2.877h2.44m-8.339-11.51h8.338M23.825 25V14.113m0 10.887a5.755 5.755 0 1 0 5.755-5.755h-5.755M37.775 25h2.692m-5.092 5.795l1.903 1.903m-7.698.497v2.692m5.795-16.682l1.903-1.903m-7.698-.497v-2.692");
}

</style>
