<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytv7pabhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytv7pabhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:youtube-gaming-logo-2" /></template>
