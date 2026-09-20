<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kjz3gdjxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:star-and-crescent-bold" /></template>
<style>
.kjz3gdjxl {
  fill: currentColor;
  d: path("M157.46 195.72a76 76 0 0 1 0-135.44a12 12 0 0 0 0-21.37a100 100 0 1 0 0 178.18a12 12 0 0 0 0-21.37M112 204a76 76 0 0 1 0-152a77 77 0 0 1 13.57 1.19a100.14 100.14 0 0 0 0 149.62A77 77 0 0 1 112 204m136.75-87l-24.28-10.5l-2.12-27.42a12 12 0 0 0-21.22-6.72l-17 20.58l-25.26-6.25a12 12 0 0 0-13.22 17.73L159.54 128l-13.88 23.58a12 12 0 0 0 13.22 17.73l25.26-6.25l17 20.58a12 12 0 0 0 9.26 4.36a11.9 11.9 0 0 0 3.62-.56a12 12 0 0 0 8.34-10.52l2.12-27.42l24.27-10.5a12 12 0 0 0 0-22m-40.44 13.35a12 12 0 0 0-7.21 10.09l-.39 5l-2.87-3.44a12 12 0 0 0-9.25-4.36a11.8 11.8 0 0 0-2.88.35l-4.89 1.21l3-5.07a12 12 0 0 0 0-12.18l-3-5.07l4.89 1.21a12 12 0 0 0 12.13-4l2.87-3.48l.39 5a12 12 0 0 0 7.21 10.09l5.4 2.33Z");
}

</style>
