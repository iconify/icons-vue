<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-a-u1b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:upi-pay-sharp" /></template>
<style>
.u-a-u1b-i {
  fill: currentColor;
  d: path("M11 15h1.5v-2H16V9h-5zm6 0h1.5V9H17zm-4.5-3.5v-1h2v1zM5 15h5V9H8.5v4.5h-2V9H5zm-3 5V4h20v16z");
}

</style>
