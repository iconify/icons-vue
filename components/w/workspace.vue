<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="naya-7bbj"/><path class="ubwek9_8c"/><path class="i3k03pgza"/><path class="w1qi_fv1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:workspace" /></template>
<style>
.i3k03pgza {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.793 26.677c-.593-3.78 4.209-6.979 7.152-3.42");
}

.naya-7bbj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.462 22.574c.02-.283.043-.565.043-.853c0-6.433-5.216-11.648-11.649-11.648c-5.043 0-9.325 3.21-10.946 7.694l-.02-.002a4.607 4.607 0 0 0-4.606 4.607c0 .691.163 1.341.436 1.93a7.121 7.121 0 0 0 2.905 13.626h22.097A7.78 7.78 0 0 0 42.5 30.15c0-3.697-2.581-6.785-6.038-7.576");
}

.ubwek9_8c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.739 24.088c1.793 4.406-2.09 9.308-6.128 9.308a7.314 7.314 0 0 1 0-14.627c4.011 0 5.663 4.077 5.663 4.077");
}

.w1qi_fv1l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.775 27.474c2.144-1.66.499-4.628.499-4.628c-2.796 0-6.582 7.238-10.631 2.155m9.1 1.676z");
}

</style>
