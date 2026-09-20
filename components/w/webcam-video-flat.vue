<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smmnezbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smmnezbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:webcam-video-flat" /></template>
