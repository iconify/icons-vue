<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bviffr9jx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rhombus-16-filled" /></template>
<style>
.bviffr9jx {
  fill: currentColor;
  d: path("M3.892 4.069A1.75 1.75 0 0 1 5.504 3h7.748a1.75 1.75 0 0 1 1.611 2.431l-2.747 6.502a1.75 1.75 0 0 1-1.612 1.069H2.756a1.75 1.75 0 0 1-1.612-2.432z");
}

</style>
