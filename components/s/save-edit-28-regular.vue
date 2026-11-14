<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="nazh-ovjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:save-edit-28-regular" /></template>
<style>
.nazh-ovjv {
  fill: currentColor;
  d: path("M23.1 14.67a2.286 2.286 0 0 1 3.232 3.232l-7.902 7.903a2.7 2.7 0 0 1-1.247.706l-1.831.458a1.088 1.088 0 0 1-1.319-1.319l.458-1.83c.118-.473.362-.904.706-1.248zM19.215 3a3.25 3.25 0 0 1 2.298.952l2.535 2.535c.61.61.952 1.436.952 2.298v4.227a3.3 3.3 0 0 0-1.5.22V8.785c0-.464-.185-.91-.513-1.237l-2.535-2.535a1.75 1.75 0 0 0-1.237-.513H19v4.25A2.25 2.25 0 0 1 16.75 11h-6.5A2.25 2.25 0 0 1 8 8.75V4.5H6.25A1.75 1.75 0 0 0 4.5 6.25v15.5A1.75 1.75 0 0 0 6 23.482V16.25A2.25 2.25 0 0 1 8.25 14h11.5c.712 0 1.346.33 1.758.847l-1.082 1.083a.75.75 0 0 0-.676-.43H8.25a.75.75 0 0 0-.75.75v7.25h6.044l-.023.077L13.167 25H6.25A3.25 3.25 0 0 1 3 21.75V6.25A3.25 3.25 0 0 1 6.25 3zM9.5 8.75c0 .414.336.75.75.75h6.5a.75.75 0 0 0 .75-.75V4.5h-8z");
}

</style>
