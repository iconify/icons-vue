<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2_2mi01k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o2_2mi01k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:webcam-video-flat" /></template>
