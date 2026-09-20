<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py82f8xvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:omega-24-regular" /></template>
<style>
.py82f8xvz {
  fill: currentColor;
  d: path("M12 2c5.523 0 10 4.477 10 10c0 2.553-1.238 4.727-2.521 6.3a17 17 0 0 1-2.174 2.2h3.945a.75.75 0 0 1 0 1.5h-5.17a1.075 1.075 0 0 1-1.07-.966l-.006-.11l.008-.132c.037-.305.204-.577.45-.752l.451-.339c.585-.46 1.524-1.27 2.402-2.347C19.493 15.91 20.5 14.065 20.5 12a8.5 8.5 0 0 0-17 0c0 2.065 1.007 3.91 2.185 5.354a15.5 15.5 0 0 0 2.853 2.686c.281.2.458.526.458.885c0 .594-.481 1.075-1.075 1.075H2.75a.75.75 0 0 1 0-1.5h3.945a17 17 0 0 1-2.174-2.2C3.238 16.728 2 14.554 2 12C2 6.477 6.477 2 12 2");
}

</style>
