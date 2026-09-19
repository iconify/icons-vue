<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quxz162xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-r-mobiledata" /></template>
<style>
.quxz162xh {
  fill: currentColor;
  d: path("M7.8 7.2L9 10H7L5.87 7.33H4V10H2V2h5c1.13 0 2 .87 2 2v1.33c0 .8-.53 1.54-1.2 1.87M7 4H4v1.33h3z");
}

</style>
