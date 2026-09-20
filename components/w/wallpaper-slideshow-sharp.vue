<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnawmnb3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wallpaper-slideshow-sharp" /></template>
<style>
.fnawmnb3d {
  fill: currentColor;
  d: path("M16.038 8.002q-.211-.21-.211-.52t.21-.522t.52-.21t.521.21t.21.52t-.21.521t-.52.21t-.52-.21m-6.884 5.691l1.892-2.461l1.589 1.885l2.454-3.077l2.757 3.653zM3.5 20V6.616h1V19h12.385v1zm3-10.817V3h5.808v1H7.5v5.183zM6.5 17v-5.433h1V16h4.808v1zm8.192 0v-1H19.5v-4.433h1V17zM19.5 9.183V4h-4.808V3H20.5v6.183z");
}

</style>
