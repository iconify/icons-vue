<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acddq37ag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="acddq37ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yt-dlp-web-player-dark" /></template>
