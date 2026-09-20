<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ineb06b6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:map-20-regular" /></template>
<style>
.ineb06b6t {
  fill: currentColor;
  d: path("M17.73 3.057A.5.5 0 0 1 18 3.5V13a.5.5 0 0 1-.213.41l-5 3.5a.5.5 0 0 1-.574 0L7.5 13.61l-4.713 3.3A.5.5 0 0 1 2 16.5V7a.5.5 0 0 1 .213-.41l5-3.5a.5.5 0 0 1 .574 0l4.713 3.3l4.713-3.3a.5.5 0 0 1 .518-.033M12 7.26l-4-2.8v8.28l4 2.8zm1 8.28l4-2.8V4.46l-4 2.8zm-6-2.8V4.46l-4 2.8v8.28z");
}

</style>
