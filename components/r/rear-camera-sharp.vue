<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrtp_n06l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rear-camera-sharp" /></template>
<style>
.vrtp_n06l {
  fill: currentColor;
  d: path("M16.77 7.52q.21-.209.21-.52t-.21-.52q-.209-.21-.52-.21t-.52.21q-.21.209-.21.52t.21.52q.209.21.52.21t.52-.21M12.5 19H20V5h-7.5zM3 20v-7.5h4.412l-2.1 2.1l.688.688L9.289 12L6 8.711l-.688.689l2.1 2.1H3V4h18v16z");
}

</style>
