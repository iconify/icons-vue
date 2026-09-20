<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydldh0bin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ydldh0bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:voicemail" /></template>
