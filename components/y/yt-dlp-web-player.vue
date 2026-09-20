<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knpoae5ge.css';
import '../../css/i/ipyektf-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="knpoae5ge"/><path class="ipyektf-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yt-dlp-web-player" /></template>
