<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7z741u9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-flashlight-on" /></template>
<style>
.y7z741u9a {
  fill: currentColor;
  d: path("M6 4v1h12V4c0-1.1-.9-2-2-2H8c-1.1 0-2 .9-2 2m0 3v1l2 3v9c0 1.1.9 2 2 2h4c1.1 0 2-.9 2-2v-9l2-3V7zm6 8.5c-.83 0-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5s1.5.67 1.5 1.5s-.67 1.5-1.5 1.5");
}

</style>
