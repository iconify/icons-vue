<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s68wt2biy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s68wt2biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:music-off-filled" /></template>
