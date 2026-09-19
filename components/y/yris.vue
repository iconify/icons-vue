<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="icn8i8j8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yris" /></template>
<style>
.icn8i8j8g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.05 16.342l12.77 7.446m-12.835 7.497l25.993-15.182M18.179 35.609l18.836-11.255m5.275 7.896v-16.5a4 4 0 0 0-2-3.464L26 4.036a4 4 0 0 0-4 0l-14.29 8.25a4 4 0 0 0-2 3.464v16.5a4 4 0 0 0 2 3.464L22 43.964a4 4 0 0 0 4 0l14.29-8.25a4 4 0 0 0 2-3.464");
}

</style>
