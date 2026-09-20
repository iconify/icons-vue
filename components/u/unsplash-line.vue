<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd8kf1wpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd8kf1wpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:unsplash-line" /></template>
