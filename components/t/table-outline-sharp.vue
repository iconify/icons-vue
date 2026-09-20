<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4m4gcb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:table-outline-sharp" /></template>
<style>
.l4m4gcb4g {
  fill: currentColor;
  d: path("M3 21V3h18v18zm8-6H5v4h6zm2 0v4h6v-4zm-2-2V9H5v4zm2 0h6V9h-6zM5 7h14V5H5z");
}

</style>
