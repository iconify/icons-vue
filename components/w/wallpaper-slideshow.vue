<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucb135wpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wallpaper-slideshow" /></template>
<style>
.ucb135wpf {
  fill: currentColor;
  d: path("M16.038 8.001q-.211-.21-.211-.52t.21-.52q.211-.211.52-.211t.521.21q.21.211.21.52t-.21.521t-.52.21t-.52-.21m-6.884 5.691l1.892-2.461l1.589 1.885l2.454-3.077l2.757 3.653zM5.116 20q-.691 0-1.153-.462T3.5 18.385V6.615h1v11.77q0 .23.192.423t.423.192h11.77v1zM6.5 9.183V4.616q0-.691.463-1.153T8.116 3h4.192v1H8.116q-.231 0-.424.192t-.192.423v4.568zM8.116 17q-.691 0-1.153-.462T6.5 15.385v-3.818h1v3.818q0 .23.192.423t.423.192h4.193v1zm6.576 0v-1h4.193q.23 0 .423-.192t.192-.423v-3.818h1v3.818q0 .69-.462 1.153T18.884 17zM19.5 9.183V4.616q0-.231-.192-.424T18.884 4h-4.192V3h4.193q.69 0 1.153.463t.462 1.152v4.568z");
}

</style>
