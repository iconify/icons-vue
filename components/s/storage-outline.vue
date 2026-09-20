<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fuf_rigco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:storage-outline" /></template>
<style>
.fuf_rigco {
  fill: currentColor;
  d: path("M3.73 19.577v-3.154h16.54v3.154zm1.54-.77h1.615v-1.615H5.268zM3.73 7.578V4.423h16.54v3.154zm1.54-.77h1.615V5.193H5.268zm-1.54 6.77v-3.154h16.54v3.154zm1.54-.77h1.615v-1.615H5.268z");
}

</style>
