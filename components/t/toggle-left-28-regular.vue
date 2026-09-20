<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="owclsf4-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:toggle-left-28-regular" /></template>
<style>
.owclsf4-g {
  fill: currentColor;
  d: path("M9 17a3 3 0 1 0 0-6a3 3 0 0 0 0 6M8 8a6 6 0 0 0 0 12h12a6 6 0 0 0 0-12zm-4.5 6A4.5 4.5 0 0 1 8 9.5h12a4.5 4.5 0 1 1 0 9H8A4.5 4.5 0 0 1 3.5 14");
}

</style>
