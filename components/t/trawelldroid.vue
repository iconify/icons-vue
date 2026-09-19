<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wt3tfobpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:trawelldroid" /></template>
<style>
.wt3tfobpg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m3.3 18.833l6.357 6.323a.796.796 0 0 0 1.351-.471c.277-2.293.856-6.388 1.641-8.205a1.41 1.41 0 0 1 1.326-.852c5.507.137 11.775 1.707 17.681 4.049C39.7 22.866 44.3 26.399 44.3 29.57c0 2.078-5.301 1.933-12.391 2.41c-6.372.428-15.167.473-18.713.292");
}

</style>
