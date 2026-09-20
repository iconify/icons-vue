<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbi9k2rkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:swipe-left-alt-sharp" /></template>
<style>
.gbi9k2rkf {
  fill: currentColor;
  d: path("M15 17q-1.825 0-3.187-1.137T10.1 13H5.825L7.4 14.6L6 16l-4-4l4-4l1.425 1.4l-1.6 1.6H10.1q.35-1.725 1.713-2.863T15 7q2.075 0 3.538 1.463T20 12t-1.463 3.538T15 17");
}

</style>
