<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9q8jttqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rear-camera-outline-sharp" /></template>
<style>
.p9q8jttqu {
  fill: currentColor;
  d: path("M6 15.289L9.289 12L6 8.711l-.688.689l2.1 2.1H3v1h4.412l-2.1 2.1zM16.77 7.52q.21-.21.21-.52t-.21-.521q-.209-.21-.52-.21t-.52.21q-.21.209-.21.52t.21.52q.209.21.52.21t.52-.21M12.5 19H20V5h-7.5zM3 20v-5.115h1V19h7.5V5H4v4.116H3V4h18v16zm8.5-1V5z");
}

</style>
