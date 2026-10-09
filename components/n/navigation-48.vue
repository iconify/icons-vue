<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt-rfw8yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yt-rfw8yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:navigation-48" /></template>
