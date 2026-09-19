<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9gkc3bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-broken-image" /></template>
<style>
.y9gkc3bal {
  fill: currentColor;
  d: path("M21 3v8.59l-3-3.01l-4 4.01l-4-4l-4 4l-3-3.01V3zm-3 8.42l3 3.01V21H3v-8.58l3 2.99l4-4l4 4z");
}

</style>
