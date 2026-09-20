<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3u7gvlxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j3u7gvlxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:youtube-tv-logo-solid" /></template>
