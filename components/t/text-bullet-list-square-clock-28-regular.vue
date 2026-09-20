<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="efbtwgx6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-bullet-list-square-clock-28-regular" /></template>
<style>
.efbtwgx6g {
  fill: currentColor;
  d: path("M20.5 14a6.5 6.5 0 1 1 0 13a6.5 6.5 0 0 1 0-13m.75-11A3.75 3.75 0 0 1 25 6.75v7.75a7.5 7.5 0 0 0-1.5-.874V6.75a2.25 2.25 0 0 0-2.25-2.25H6.75A2.25 2.25 0 0 0 4.5 6.75v14.5a2.25 2.25 0 0 0 2.25 2.25h6.876A7.5 7.5 0 0 0 14.5 25H6.75A3.75 3.75 0 0 1 3 21.25V6.75A3.75 3.75 0 0 1 6.75 3zm-.75 13.5a.5.5 0 0 0-.5.5v3.5a.5.5 0 0 0 .5.5h3a.5.5 0 0 0 0-1H21v-3a.5.5 0 0 0-.5-.5M8.75 18a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m0-5a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m9.058.5a7.5 7.5 0 0 0-2.406 1.5H12.75a.75.75 0 0 1 0-1.5zM8.75 8a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m11.5.5a.75.75 0 0 1 0 1.5h-7.5a.75.75 0 0 1 0-1.5z");
}

</style>
