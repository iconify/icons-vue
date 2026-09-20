<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zuie1-sgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-indent-increase-rtl-90-24-filled" /></template>
<style>
.zuie1-sgk {
  fill: currentColor;
  d: path("M16 15V6.5a1 1 0 0 1 1.993-.117L18 6.5V15a1 1 0 0 1-1.993.117zV6.5zm-6.707 6.707a1 1 0 0 1-.083-1.32l.083-.094l2-2a1 1 0 0 1 1.32-.083l.094.083l2 2a1 1 0 0 1-1.32 1.497l-.094-.083L12 20.414l-1.293 1.293a1 1 0 0 1-1.414 0M11 15l-.001-11.5a1 1 0 0 1 1.993-.117L13 3.5V15a1 1 0 0 1-1.993.117zl-.001-11.5zm-5 0V6.5a1 1 0 0 1 1.993-.117L8 6.5V15a1 1 0 0 1-1.993.117zV6.5z");
}

</style>
