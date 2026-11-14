<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cggxxobcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:state-store" /></template>
<style>
.cggxxobcf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.625 2.75h4.75q2.848 0 4.861 2.014t2.014 4.861v4.75q0 2.848-2.014 4.861t-4.861 2.014h-4.75q-2.848 0-4.861-2.014T2.75 14.375v-4.75q0-2.848 2.014-4.861T9.625 2.75M12 6.5Q7.25 6.5 7.25 9v6q0 2.5 4.75 2.5t4.75-2.5V9q0-2.5-4.75-2.5m3.25 4.52q-1.169.48-3.25.48t-3.25-.48V15q0 1 3.25 1t3.25-1z");
}

</style>
