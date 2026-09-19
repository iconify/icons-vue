<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylp2ribfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-where-to-vote" /></template>
<style>
.ylp2ribfm {
  fill: currentColor;
  d: path("M12 2C8.14 2 5 5.14 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.86-3.14-7-7-7m-1.53 12l-3.48-3.48L8.4 9.1l2.07 2.07l5.13-5.14l1.41 1.42z");
}

</style>
