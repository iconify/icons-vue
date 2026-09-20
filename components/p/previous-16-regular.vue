<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x2ezgpbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:previous-16-regular" /></template>
<style>
.x2ezgpbiw {
  fill: currentColor;
  d: path("M2 2.5a.5.5 0 0 1 1 0v11a.5.5 0 0 1-1 0zm12 .502a1 1 0 0 0-1.579-.816l-7 4.963a1 1 0 0 0-.006 1.628l7 5.037A1 1 0 0 0 14 13.003zM6 7.965l7-4.963v10z");
}

</style>
