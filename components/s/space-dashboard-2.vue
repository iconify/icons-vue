<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwbtdpstm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:space-dashboard-2" /></template>
<style>
.cwbtdpstm {
  fill: currentColor;
  d: path("M20 20V4zM5.615 20H13.5V4H5.616q-.691 0-1.153.463T4 5.616v12.769q0 .69.463 1.153T5.616 20m8.884 0h3.885q.69 0 1.152-.462T20 18.385V12.5h-5.5zm0-8.5H20V5.616q0-.691-.462-1.153T18.384 4H14.5z");
}

</style>
