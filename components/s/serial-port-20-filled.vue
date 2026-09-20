<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uoytkmf8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:serial-port-20-filled" /></template>
<style>
.uoytkmf8o {
  fill: currentColor;
  d: path("M2.334 9.067A2.5 2.5 0 0 1 4.769 6h10.46a2.5 2.5 0 0 1 2.435 3.068l-.7 3A2.5 2.5 0 0 1 14.529 14H5.467a2.5 2.5 0 0 1-2.435-1.933zM6 9.5a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1M8.5 9a.5.5 0 1 0-1 0a.5.5 0 0 0 1 0M7 11.5a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1m2.5-.5a.5.5 0 1 0-1 0a.5.5 0 0 0 1 0m1.5.5a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1m2.5-.5a.5.5 0 1 0-1 0a.5.5 0 0 0 1 0M10 9.5a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1m2.5-.5a.5.5 0 1 0-1 0a.5.5 0 0 0 1 0m1.5.5a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

</style>
