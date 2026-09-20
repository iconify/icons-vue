<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyqszob2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:usb-stick-24-filled" /></template>
<style>
.eyqszob2v {
  fill: currentColor;
  d: path("M15.267 1.997a.75.75 0 0 1 .743.648l.007.102v4.386a2.25 2.25 0 0 1 1.48 1.946l.007.17v10.5a2.25 2.25 0 0 1-2.096 2.246l-.154.005h-6.5a2.25 2.25 0 0 1-2.245-2.096l-.005-.154V9.25a2.25 2.25 0 0 1 1.513-2.127V2.747a.75.75 0 0 1 .648-.743l.101-.007zm-.75 1.5H9.516v3.502h5.001z");
}

</style>
