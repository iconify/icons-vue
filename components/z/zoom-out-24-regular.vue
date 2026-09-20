<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbckw1y8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:zoom-out-24-regular" /></template>
<style>
.lbckw1y8e {
  fill: currentColor;
  d: path("M12.75 9.25a.75.75 0 0 1 0 1.5h-5.5a.75.75 0 0 1 0-1.5zM10 2a8 8 0 0 1 6.162 13.102l4.618 4.618a.75.75 0 0 1-1.06 1.06l-4.618-4.618A8 8 0 1 1 10 2m0 1.5a6.5 6.5 0 1 0 0 13a6.5 6.5 0 0 0 0-13");
}

</style>
