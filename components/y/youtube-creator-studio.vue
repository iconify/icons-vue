<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9hbzbcjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9hbzbcjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:youtube-creator-studio" /></template>
