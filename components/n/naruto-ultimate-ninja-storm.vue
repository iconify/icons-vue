<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uy6jdygzk"/><path class="wbn__7bgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:naruto-ultimate-ninja-storm" /></template>
<style>
.uy6jdygzk {
  fill: none;
  stroke: currentColor;
  stroke-dashoffset: 3;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.731 10.136l-5.786 4.03C30.282 8.62 20.404 8.713 14.84 15.63c-3.547 4.41-3.876 8.966-2.99 13.414c1.37 6.889 8.558 9.611 14.764 8.623c5.95-.947 9.856-4.332 9.497-9.76c-.58-8.776-10.564-13.054-16.356-8.517c-3.244 2.542-3.48 10.694 3.944 11.36c2.765.248 5.349-1.509 5.33-4.348c-.017-2.652-2.868-3.272-3.657-3.287");
}

.wbn__7bgj {
  fill: none;
  stroke: currentColor;
  stroke-dashoffset: 3;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.793 21.81c-1.576 6.283-3.866 10.978-6.524 15.497c5.035-.325 8.477-.648 16.57.387");
}

</style>
