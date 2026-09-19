<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lu2ptpdtr"/><path class="w9nyjicgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:renee-cosmetics" /></template>
<style>
.lu2ptpdtr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.349 33.008v-8h2.618c1.48 0 2.681 1.204 2.681 2.687s-1.2 2.687-2.68 2.687h-2.62m2.619 0l2.619 2.624m1.913-3.998h2.608m1.392 4h-4v-7.999h4m9.001 3.999h2.608m1.392 4h-4v-7.999h4m1.851 3.999h2.608m1.392 4h-4v-7.999h4M22.35 33.008v-7.999l5.299 7.999v-7.999");
}

.w9nyjicgo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.363 19.846h-7.86L25.736 6.848a2 2 0 0 0-3.5 0l-7.769 12.998h-7.86a3.12 3.12 0 0 0-3 3.93l4.38 16.308a2.84 2.84 0 0 0 2.74 2.1h26.496a2.84 2.84 0 0 0 2.76-2.1l4.41-16.309a3.12 3.12 0 0 0-3.03-3.929m-17.378-8l4.77 8h-9.54z");
}

</style>
