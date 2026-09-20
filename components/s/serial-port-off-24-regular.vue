<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukxy7xbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:serial-port-off-24-regular" /></template>
<style>
.ukxy7xbfs {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l18.5 18.5a.75.75 0 0 1-1.06 1.06l-4.78-4.779H5.98a2.75 2.75 0 0 1-2.675-2.113l-1.072-4.501A2.75 2.75 0 0 1 4.907 7H5.94L2.22 3.28a.75.75 0 0 1 0-1.06M19.092 7a2.75 2.75 0 0 1 2.675 3.388l-1.075 4.502a2.74 2.74 0 0 1-1.047 1.574l-1.087-1.088c.33-.16.586-.46.675-.835l1.075-4.501a1.25 1.25 0 0 0-1.216-1.54h-7.41l-1.5-1.5zM4.907 8.5a1.25 1.25 0 0 0-1.216 1.54l1.072 4.5c.134.563.637.96 1.216.961h8.461l-4.325-4.325a.748.748 0 0 1-1.365-.426a.75.75 0 0 1 .322-.617L7.44 8.5zm3.343 4a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5m2.5 0a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5M7 10a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5m10 0a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5m-2.5 0a.75.75 0 0 1 .163 1.481l-.894-.894A.75.75 0 0 1 14.5 10");
}

</style>
