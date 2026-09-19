<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hj5q03bru"/><path class="r__1fb1_r"/><path class="lobeuyb2y"/><path class="k-exddbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-notes" /></template>
<style>
.hj5q03bru {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.488 23.42A10.283 10.283 0 0 0 24.946 8.879");
}

.k-exddbmh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.409 40.212a7.18 7.18 0 0 0-4.725-4.91");
}

.lobeuyb2y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.831 22.994L5.5 42.134l20.003-4.728");
}

.r__1fb1_r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.426 35.818a5.1 5.1 0 0 1 1.077 1.588L39.488 23.42L24.946 8.878L10.831 22.994a5.04 5.04 0 0 1 2.025 1.254c1.597 1.597 1.918 3.867.715 5.07c1.203-1.203 3.473-.883 5.07.715s1.918 3.867.715 5.07c1.203-1.203 3.472-.883 5.07.715");
}

</style>
