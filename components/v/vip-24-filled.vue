<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8z6btbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vip-24-filled" /></template>
<style>
.k8z6btbgq {
  fill: currentColor;
  d: path("M18.75 4A3.25 3.25 0 0 1 22 7.25v9.5A3.25 3.25 0 0 1 18.75 20H5.25A3.25 3.25 0 0 1 2 16.75v-9.5A3.25 3.25 0 0 1 5.25 4zm-8.744 4.545a.75.75 0 0 0-.961.45L7.5 13.242L5.955 8.994a.75.75 0 0 0-1.41.512L6.46 14.77a1.107 1.107 0 0 0 2.08 0l1.915-5.265a.75.75 0 0 0-.45-.961M12.25 8.5a.75.75 0 0 0-.75.75v5.5a.75.75 0 0 0 1.5 0v-5.5a.75.75 0 0 0-.75-.75m3 0a.75.75 0 0 0-.75.75v5.5a.75.75 0 0 0 1.5 0V13h1.25a2.25 2.25 0 0 0 0-4.5zm2 1.5a.75.75 0 0 1 0 1.5H16V10z");
}

</style>
