<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sko1rsesz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-1x-mobiledata" /></template>
<style>
.sko1rsesz {
  fill: currentColor;
  d: path("M4 7h4v10H6V9H4zm11.83 4.72L18.66 7h-2.33l-1.66 2.77L13 7h-2.33l2.83 4.72L10.33 17h2.33l2-3.34l2 3.34H19z");
}

</style>
