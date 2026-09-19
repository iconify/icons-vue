<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukk5zubmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ukk5zubmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:seven-of-circles-mahjong-filled" /></template>
