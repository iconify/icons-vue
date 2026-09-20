<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8g-il35d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8g-il35d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:webcam-video-solid" /></template>
