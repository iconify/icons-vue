<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwd_oeb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-home-24-regular" /></template>
<style>
.qwd_oeb2n {
  fill: currentColor;
  d: path("M16.524 12.36a1.5 1.5 0 0 1 1.952 0l4 3.427c.332.285.524.7.524 1.139V22a1 1 0 0 1-1 1h-1.667a1 1 0 0 1-1-1v-3a1 1 0 0 0-1-1h-1.666a1 1 0 0 0-1 1v3a1 1 0 0 1-1 1H13a1 1 0 0 1-1-1v-5.074a1.5 1.5 0 0 1 .524-1.139zm-4.65 2.667q-.244.212-.423.473H6.253a.75.75 0 0 0-.75.749v.577c0 .536.192 1.054.54 1.461C7.138 19.57 8.777 20.301 11 20.465v1.502c-2.655-.176-4.702-1.07-6.098-2.705a3.75 3.75 0 0 1-.898-2.436v-.577A2.25 2.25 0 0 1 6.253 14h6.82zM12 2.005a5 5 0 1 1 0 10a5 5 0 0 1 0-10m0 1.5a3.5 3.5 0 1 0 0 7a3.5 3.5 0 0 0 0-7");
}

</style>
