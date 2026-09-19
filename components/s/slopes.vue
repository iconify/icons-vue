<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zw016zt4r"/><path class="zl3jurbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:slopes" /></template>
<style>
.zl3jurbur {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.293 38.245c8.657-3.738 13.193-7.234 3.792-10.746c-4.349-1.86-12.238-3.55-6.897-6.952c-6.53 2.823-1.181 5.475 1.97 6.422c11.981 3.628 5.349 6.295-3.668 9.29");
}

.zw016zt4r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 22.769l.79.727l3.433-3.745l.579.796l4.121-5.247l5.765 5.247L31.965 9.755l7.868 11.535l2.667 2.784");
}

</style>
