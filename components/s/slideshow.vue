<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vic1rbbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="vic1rbbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:slideshow" /></template>
