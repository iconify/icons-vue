<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m7z2l_bdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tp-postman-agent" /></template>
<style>
.m7z2l_bdj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.5 9.9l-3.65.159c-1.698.073-1.947.695-2.443 2.311l-5.493 17.904c-.232.755-1.168 1.338-1.96 1.338H8.86c-.725 0-1.491-.774-1.582-1.493L5.525 16.213c-.135-1.07.283-1.66 1.289-1.66h28.785l-16.06 9.773c-1.01.614-2.674.797-3.546 0l-10.07-9.21m16.862 7.355l7.264 8.619m-15.264-7.57l-6.683 7.452m3.752 5.016A2.11 2.11 0 0 1 9.742 38.1h0a2.112 2.112 0 1 1 2.112-2.11m18.563-.002a2.112 2.112 0 0 1-4.226 0h0c0-1.166.946-2.111 2.113-2.111h0c1.167 0 2.113.945 2.113 2.111");
}

</style>
