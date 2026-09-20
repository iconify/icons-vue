<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yfwjwbv8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-bold-16-regular" /></template>
<style>
.yfwjwbv8a {
  fill: currentColor;
  d: path("M4 3.1C4 2.5 4.5 2 5.1 2h3c2.1 0 3.4 1.4 3.4 3.4c0 .9-.3 2-.7 2.6c.8.6 1.4 1.2 1.4 2.5c0 2.7-2.1 3.5-3.6 3.5H5.1c-.6 0-1.1-.5-1.1-1.1zM6 9v3h2.4c.7 0 1.5-.5 1.5-1.5S9.1 9 8.4 9zm0-2h2.2c.9 0 1.5-.7 1.5-1.5S9.1 4 8.3 4H6z");
}

</style>
