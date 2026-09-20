<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="te22ygzhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-indent-decrease-20-regular" /></template>
<style>
.te22ygzhy {
  fill: currentColor;
  d: path("M6 4.5a.5.5 0 0 1 .5-.5h8a.5.5 0 1 1 0 1h-8a.5.5 0 0 1-.5-.5M3.56 7.732a.5.5 0 0 1 .708.707L3.208 9.5l1.06 1.06a.5.5 0 1 1-.707.708L2.146 9.854a.5.5 0 0 1 0-.708zM6.5 9a.5.5 0 0 0 0 1h11a.5.5 0 1 0 0-1zM6 14.5a.5.5 0 0 1 .5-.5h6a.5.5 0 1 1 0 1h-6a.5.5 0 0 1-.5-.5");
}

</style>
