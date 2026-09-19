<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hzb39mbiz"/><path class="fnepqnbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rmvgo" /></template>
<style>
.fnepqnbkn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.635 19.392H40.26s5.101 5.43 4.113 8.282c-.296.856-3.089.934-3.089.934h-30.72zm-2.385 0l-3.07 9.216zm-2.318 0l-3.073 9.216zm-2.36 0L3.5 28.608z");
}

.hzb39mbiz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.366 27.009v-6.018h1.97c1.114 0 2.017.905 2.017 2.021s-.903 2.021-2.017 2.021h-1.97m1.97 0l1.97 1.975m2.823-.005v-6.012l3.009 6.018L30.148 21v6.009m6.674-6.018l-1.993 6.018l-1.994-6.018");
}

</style>
