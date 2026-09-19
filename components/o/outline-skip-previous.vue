<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hef6o_beo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-skip-previous" /></template>
<style>
.hef6o_beo {
  fill: currentColor;
  d: path("M6 6h2v12H6zm3.5 6l8.5 6V6zm6.5 2.14L12.97 12L16 9.86z");
}

</style>
