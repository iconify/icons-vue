<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wwofuvz_c"/><path class="dmwqcebti"/><path class="jk_3ghbyh"/><path class="shth5ccdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wadoku" /></template>
<style>
.dmwqcebti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.59 29.458V18.144h4.405v11.362m-4.405-1.823H22M13.457 17.55v12.43m-3.247-8.847h6.108m-5.904-3.131c1.77-.156 3.808-.523 5.412-1.118M9.96 27.395c1.567-1.936 2.785-4.004 3.47-6.275q-.343 1.117 2.607 4.246m9.41-8.622c3.656 3.391 3.02 8.338 2.55 11.678c-.16 1.144-.81 1.313-2.403 1.25");
}

.jk_3ghbyh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.966 16.816c-1.079 1.671-2.286 3.098-3.61 4.305m2.914 1.489c-.926 1.267-1.867 2.503-2.971 3.397m5.166-6.417v4.543h6.585v-4.542zm3.247-3.249v12.382m-4.155.474c2.708-.266 5.315-.582 7.63-1.043");
}

.shth5ccdu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.142 25.9c.628 1.295 1.325 2.58 1.498 3.938");
}

.wwofuvz_c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.796 5.5h16.35L42.5 16.507V31.64L32.145 42.5h-16.35L5.5 31.64V16.507z");
}

</style>
