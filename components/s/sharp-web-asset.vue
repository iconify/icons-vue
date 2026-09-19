<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_0xr7bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-web-asset" /></template>
<style>
.a_0xr7bkz {
  fill: currentColor;
  d: path("M3 4v16h18V4zm16 14H5V8h14z");
}

</style>
