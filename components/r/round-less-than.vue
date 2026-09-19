<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="co9uueblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-less-than" /></template>
<style>
.co9uueblr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m16.75 17l-7.5-5l7.5-5a.901.901 0 1 0-1-1.5l-8.502 5.668a1 1 0 0 0 0 1.664L15.75 18.5a.901.901 0 1 0 1-1.5");
}

</style>
