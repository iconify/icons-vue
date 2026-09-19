<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gofkv4bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-divide" /></template>
<style>
.gofkv4bvi {
  fill: currentColor;
  d: path("M6 11h12a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2m6.002-7a2 2 0 1 0-.004 4a2 2 0 0 0 .004-4m0 12a2 2 0 1 0-.004 4a2 2 0 0 0 .004-4");
}

</style>
