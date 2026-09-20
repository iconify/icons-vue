<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/diklabb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="diklabb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:video-movies-play" /></template>
