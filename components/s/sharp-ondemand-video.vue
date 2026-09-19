<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbu6i0b0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-ondemand-video" /></template>
<style>
.mbu6i0b0w {
  fill: currentColor;
  d: path("M23 3H1v16h7v2h8v-2h6.99zm-2 14H3V5h18zm-5-6l-7 4V7z");
}

</style>
