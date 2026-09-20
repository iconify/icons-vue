<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da5g7rbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-warning-24-filled" /></template>
<style>
.da5g7rbmd {
  fill: currentColor;
  d: path("m16.161 1.83l-3.997 7.998A1.5 1.5 0 0 0 13.507 12h7.994a1.5 1.5 0 0 0 1.343-2.172L18.847 1.83c-.553-1.107-2.133-1.107-2.686 0m1.843 2.666v3.001a.5.5 0 0 1-1 0V4.496a.5.5 0 0 1 1 0m-.5 5.503a.5.5 0 1 1 0-1.001a.5.5 0 0 1 0 1M21.5 13h-7.884l-1.268.664a.75.75 0 0 1-.696 0L2 8.608v8.142l.005.184A3.25 3.25 0 0 0 5.25 20h13.5l.184-.005A3.25 3.25 0 0 0 22 16.75v-3.799q-.241.048-.5.049M5.25 4h8.71l-2.69 5.38a2.48 2.48 0 0 0 .125 2.456L2.016 6.924a3.25 3.25 0 0 1 3.048-2.919z");
}

</style>
