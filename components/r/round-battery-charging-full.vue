<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyw_ovp6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-battery-charging-full" /></template>
<style>
.wyw_ovp6a {
  fill: currentColor;
  d: path("M15.67 4H14V3c0-.55-.45-1-1-1h-2c-.55 0-1 .45-1 1v1H8.33C7.6 4 7 4.6 7 5.33v15.33C7 21.4 7.6 22 8.34 22h7.32c.74 0 1.34-.6 1.34-1.33V5.33C17 4.6 16.4 4 15.67 4m-1.06 9.24l-2.67 5c-.24.45-.94.28-.94-.24v-3.5H9.83a.5.5 0 0 1-.44-.74l2.67-5c.24-.45.94-.28.94.24v3.5h1.17c.37 0 .62.4.44.74");
}

</style>
