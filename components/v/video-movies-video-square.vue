<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4bm74j-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x4bm74j-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:video-movies-video-square" /></template>
