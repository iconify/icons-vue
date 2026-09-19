<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hl1yp6bnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:writer" /></template>
<style>
.hl1yp6bnj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12 30.872h11.462M12 23.915h11.462M12 16.957h4.487m27.013 7.24V9.402L30.646 16.8zm-5.396 1.956v10.43a4 4 0 0 1-4 4H8.5a4 4 0 0 1-4-4V11.417a4 4 0 0 1 4-4h29.653");
}

</style>
