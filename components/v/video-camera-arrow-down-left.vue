<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx6ys8baq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx6ys8baq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:video-camera-arrow-down-left" /></template>
