<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="z1cmilbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:minsundhed" /></template>
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

.z1cmilbiy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.714 21.473c1.308.914.623 3.325-2.97 6.258c0 0-2.801-2.12-2.85-4.17s1.749-1.99 2.543.282c0 0 1.97-3.284 3.277-2.37m19.961 0c1.308.914.623 3.325-2.97 6.258c0 0-2.801-2.12-2.85-4.17s1.749-1.99 2.543.282c0 0 1.97-3.284 3.277-2.37m-7.77 12.528h-9.81s.477 5.439 4.947 5.439S28.905 34 28.905 34");
}

</style>
