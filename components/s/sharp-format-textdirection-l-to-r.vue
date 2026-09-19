<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw1bwcbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-format-textdirection-l-to-r" /></template>
<style>
.zw1bwcbta {
  fill: currentColor;
  d: path("M9 10v5h2V4h2v11h2V4h2V2H9C6.79 2 5 3.79 5 6s1.79 4 4 4m12 8l-4-4v3H5v2h12v3z");
}

</style>
