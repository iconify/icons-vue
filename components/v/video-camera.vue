<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m06gt_svh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m06gt_svh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:video-camera" /></template>
