<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydiqtgbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:rear-camera-outline" /></template>
<style>
.ydiqtgbnl {
  fill: currentColor;
  d: path("M6 15.289L9.289 12L6 8.711l-.688.689l2.1 2.1H3v1h4.412l-2.1 2.1zM16.77 7.52q.21-.21.21-.52t-.21-.52t-.52-.21t-.52.21t-.21.52t.21.52t.52.21t.52-.21M12.5 19h6.885q.23 0 .423-.192t.192-.424V5.616q0-.231-.192-.424T19.385 5H12.5zm-7.884 1q-.691 0-1.153-.462T3 18.384v-3.5h1v3.5q0 .231.192.424t.423.192H11.5V5H4.616q-.231 0-.424.192T4 5.616v3.5H3v-3.5q0-.691.463-1.153T4.615 4h14.77q.69 0 1.152.463T21 5.616v12.769q0 .69-.463 1.153T19.385 20zM11.5 5.616V5v14z");
}

</style>
