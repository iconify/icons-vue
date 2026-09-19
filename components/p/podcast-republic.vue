<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cr7868b7d"/><path class="e_zjo-bvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:podcast-republic" /></template>
<style>
.cr7868b7d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.191 7.021a21.5 21.5 0 1 0 0 33.958m3.093-2.939a21.5 21.5 0 0 0 0-28.08");
}

.e_zjo-bvc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.752 22.564l-11.847-6.84a1.658 1.658 0 0 0-2.486 1.436v13.68a1.658 1.658 0 0 0 2.486 1.436l11.847-6.84a1.658 1.658 0 0 0 0-2.872");
}

</style>
