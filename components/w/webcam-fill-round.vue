<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zca_fftim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zca_fftim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:webcam-fill-round" /></template>
