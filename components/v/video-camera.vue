<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv4o2cnxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wv4o2cnxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:video-camera" /></template>
