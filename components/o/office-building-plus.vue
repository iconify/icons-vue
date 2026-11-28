<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii3yt_r-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii3yt_r-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:office-building-plus" /></template>
