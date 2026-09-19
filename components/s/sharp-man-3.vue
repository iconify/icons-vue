<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw8f57zpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-man-3" /></template>
<style>
.uw8f57zpo {
  fill: currentColor;
  d: path("M16 7H8v8h2v7h4v-7h2zm-4-5.249L14.248 4L12 6.248L9.75 4z");
}

</style>
