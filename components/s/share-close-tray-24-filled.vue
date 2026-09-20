<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mokozebfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:share-close-tray-24-filled" /></template>
<style>
.mokozebfj {
  fill: currentColor;
  d: path("M4.25 20A2.25 2.25 0 0 1 2 17.75V6.25A2.25 2.25 0 0 1 4.25 4h15.5A2.25 2.25 0 0 1 22 6.25v11.5A2.25 2.25 0 0 1 19.75 20zm8.28-3.465l3.255-3.255a.75.75 0 1 0-1.06-1.06l-1.975 1.974V7.747a.75.75 0 0 0-1.5 0v6.445L9.28 12.22a.75.75 0 1 0-1.06 1.06l3.25 3.255a.75.75 0 0 0 1.06 0");
}

</style>
