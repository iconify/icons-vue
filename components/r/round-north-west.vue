<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvcpyme2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-north-west" /></template>
<style>
.tvcpyme2u {
  fill: currentColor;
  d: path("M6 15c.56 0 1-.45 1-1V8.41L17.89 19.3a.996.996 0 1 0 1.41-1.41L8.41 7H14c.55 0 1-.45 1-1s-.45-1-1-1H6c-.55 0-1 .45-1 1v8c0 .55.45 1 1 1");
}

</style>
