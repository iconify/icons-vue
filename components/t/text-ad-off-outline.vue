<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4fpo6bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:text-ad-off-outline" /></template>
<style>
.m4fpo6bpy {
  fill: currentColor;
  d: path("M5.73 15.885v-1h9.155l1 1zm0-3.385v-1h5.77l1 1zm0-3.384v-1h2.386l1 1zm9.582 3.384h2.957v-1h-3.957zm-3.385-3.384H14.5v-1h-3.573zm8.925 8.925L20 17.189V6.616q0-.27-.173-.443T19.385 6H8.81l-1-1h11.574q.69 0 1.153.463T21 6.616v10.769q0 .173-.04.343t-.108.313m.252 4.49L17.573 19H4.616q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5H5l1 1H4.616q-.231 0-.424.192T4 6.616v10.769q0 .23.192.423t.423.192h11.958L1.881 3.308l.713-.714l19.223 19.223z");
}

</style>
