<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srxdbmbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-width-normal" /></template>
<style>
.srxdbmbht {
  fill: currentColor;
  d: path("M22 4H2v16h20zM4 6h4v12H4zm16 12h-4V6h4z");
}

</style>
