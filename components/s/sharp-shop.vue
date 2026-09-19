<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qc8odol1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-shop" /></template>
<style>
.qc8odol1s {
  fill: currentColor;
  d: path("M16 6V4c0-1.1-.9-2-2-2h-4c-1.1 0-2 .9-2 2v2H2v15h20V6zm-6-2h4v2h-4zM9 18V9l7.5 4z");
}

</style>
