<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hcxmfvd6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:micts" /></template>
<style>
.hcxmfvd6e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.342 13.758C14.4 13.58.725 19.914 5.47 29.804c.888 1.852 2.605 3.482 5.06 4.741c3.358 1.723 12.31 3.493 20.691 1.44c7.031-1.722 11.116-5.851 12.076-10.057c.515-2.254.06-4.565-1.538-6.704c-5.903-7.895-21.043-8.132-25.641-8.132");
}

</style>
