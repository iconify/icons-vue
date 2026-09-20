<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gprafr8-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:triangle-right-16-regular" /></template>
<style>
.gprafr8-d {
  fill: currentColor;
  d: path("M14.222 6.687a1.5 1.5 0 0 1 0 2.629l-10 5.499A1.5 1.5 0 0 1 2 13.5V2.502a1.5 1.5 0 0 1 2.223-1.314zm-.482 1.752a.5.5 0 0 0 0-.876l-10-5.499a.5.5 0 0 0-.74.438v10.999a.5.5 0 0 0 .741.438z");
}

</style>
