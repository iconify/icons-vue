<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwxzxzmiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:memory-alt-outline" /></template>
<style>
.dwxzxzmiv {
  fill: currentColor;
  d: path("M6.5 14.5h1v-5h-1zm5 0h1v-5h-1zm5 0h1v-5h-1zM4.616 17h14.769q.23 0 .423-.192t.192-.424V7.616q0-.231-.192-.424T19.385 7H4.615q-.23 0-.423.192T4 7.616v8.769q0 .23.192.423t.423.192M4 17V7zm1.5 3v-2h-.885q-.69 0-1.153-.462T3 16.384V7.616q0-.691.463-1.153T4.615 6H5.5V4h1v2h5V4h1v2h5V4h1v2h.885q.69 0 1.152.463T21 7.616v8.769q0 .69-.463 1.153T19.385 18H18.5v2h-1v-2h-5v2h-1v-2h-5v2z");
}

</style>
