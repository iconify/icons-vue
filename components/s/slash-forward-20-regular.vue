<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a1igh8b4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slash-forward-20-regular" /></template>
<style>
.a1igh8b4b {
  fill: currentColor;
  d: path("M12.658 2.026a.5.5 0 0 1 .317.632l-5 15a.5.5 0 1 1-.95-.316l5-15a.5.5 0 0 1 .633-.316");
}

</style>
