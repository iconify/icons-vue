<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cwo6q22hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:omnivore" /></template>
<style>
.cwo6q22hr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.579 32.062v-12.84c0-1.442 1.862-2.02 2.679-.83l4.371 6.364a2.234 2.234 0 0 0 3.683 0l4.371-6.365c.817-1.189 2.68-.611 2.68.832v7.385a6.069 6.069 0 0 0 12.138 0V24C45.499 11.672 35.123 1.767 22.627 2.543c-10.707.664-19.42 9.378-20.085 20.085C1.767 35.124 11.672 45.5 24 45.5");
}

</style>
