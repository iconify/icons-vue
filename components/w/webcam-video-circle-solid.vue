<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcij4pbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lcij4pbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:webcam-video-circle-solid" /></template>
