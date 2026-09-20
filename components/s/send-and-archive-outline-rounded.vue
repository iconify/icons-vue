<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fa37n8xic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:send-and-archive-outline-rounded" /></template>
<style>
.fa37n8xic {
  fill: currentColor;
  d: path("M16.423 17.927L14.896 16.4q-.111-.111-.263-.121t-.283.121t-.13.273t.13.273l1.892 1.893q.243.242.566.242t.565-.242l1.893-1.893q.111-.111.12-.263q.01-.152-.12-.283q-.131-.13-.274-.13t-.273.13l-1.527 1.527v-3.715q0-.154-.111-.27q-.112-.115-.273-.115t-.274.115q-.111.116-.111.27zm-12.23-.612v-10.7q0-.453.36-.693t.764-.058L14.966 10q.244.101.296.298t-.023.375t-.25.28q-.176.103-.439-.001L5.192 7v3.885l2.274.524q.236.06.354.22t.119.367t-.119.373t-.354.221l-2.274.525V17l5.13-2.171q.224-.104.395-.01q.171.093.247.268q.077.175.025.371q-.052.197-.297.298L5.323 18.06q-.404.18-.767-.056t-.364-.69m9.78 2.137q-1.164-1.164-1.164-2.835t1.164-2.836t2.836-1.164q1.67 0 2.835 1.164t1.165 2.836q0 1.67-1.165 2.835t-2.835 1.165t-2.836-1.165M9.444 12");
}

</style>
