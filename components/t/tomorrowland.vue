<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg5vk18uq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg5vk18uq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:tomorrowland" /></template>
