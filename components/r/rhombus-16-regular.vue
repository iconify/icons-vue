<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vvqzphmxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rhombus-16-regular" /></template>
<style>
.vvqzphmxl {
  fill: currentColor;
  d: path("M3.892 4.069A1.75 1.75 0 0 1 5.504 3h7.748a1.75 1.75 0 0 1 1.611 2.431l-2.747 6.502a1.75 1.75 0 0 1-1.612 1.069H2.756a1.75 1.75 0 0 1-1.612-2.432zM5.504 4a.75.75 0 0 0-.691.458L2.065 10.96a.75.75 0 0 0 .69 1.042h7.749a.75.75 0 0 0 .69-.458l2.748-6.502A.75.75 0 0 0 13.252 4z");
}

</style>
