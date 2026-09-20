<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="thms__oyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:stack-32-regular" /></template>
<style>
.thms__oyu {
  fill: currentColor;
  d: path("M2 7a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3zm3-1a1 1 0 0 0-1 1v10a1 1 0 0 0 1 1h14a1 1 0 0 0 1-1V7a1 1 0 0 0-1-1zm5.17 20A3 3 0 0 0 13 28h6c6.074 0 11-4.925 11-11v-2a3 3 0 0 0-2-2.83V17a9 9 0 0 1-9 9zM9 24a3 3 0 0 1-2.83-2H19a5 5 0 0 0 5-5V8.17c1.164.412 2 1.524 2 2.83v6a7 7 0 0 1-7 7z");
}

</style>
