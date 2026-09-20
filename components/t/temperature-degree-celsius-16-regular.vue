<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="js2hepbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:temperature-degree-celsius-16-regular" /></template>
<style>
.js2hepbyr {
  fill: currentColor;
  d: path("M2.5 5a1 1 0 1 1 2 0a1 1 0 0 1-2 0m1-2a2 2 0 1 0 0 4a2 2 0 0 0 0-4m7 1C8.603 4 7 5.493 7 8s1.603 4 3.5 4a3.33 3.33 0 0 0 2.935-1.704a.57.57 0 0 1 .488-.296c.362 0 .613.36.441.68C13.584 12.127 12.16 13 10.5 13C7.98 13 6 10.985 6 8s1.98-5 4.5-5c1.66 0 3.085.872 3.864 2.32c.172.32-.08.68-.441.68a.57.57 0 0 1-.488-.296A3.33 3.33 0 0 0 10.5 4");
}

</style>
