<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xubs-on4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-edit-style-16-regular" /></template>
<style>
.xubs-on4w {
  fill: currentColor;
  d: path("M5 2a.5.5 0 0 1 .471.332l1.862 5.214l-.782.782L6.076 7H3.924L2.97 9.668a.5.5 0 0 1-.942-.336l2.5-7A.5.5 0 0 1 5 2m.72 4L5 3.987L4.281 6zm7.72-.438a1.914 1.914 0 0 0-2.708 0l-4.657 4.657a2.5 2.5 0 0 0-.684 1.277l-.381 1.906a.5.5 0 0 0 .588.589l1.906-.382a2.5 2.5 0 0 0 1.278-.683l4.657-4.657a1.915 1.915 0 0 0 0-2.707m-2.001.707a.914.914 0 1 1 1.293 1.293L8.075 12.22a1.5 1.5 0 0 1-.767.41l-1.17.234l.234-1.17a1.5 1.5 0 0 1 .41-.767z");
}

</style>
