<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt_3x2brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt_3x2brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:tower-check" /></template>
