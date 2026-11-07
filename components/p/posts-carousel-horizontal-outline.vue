<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1jmd4bmi.css';
import '../../css/h/haze59b4w.css';
import '../../css/z/zyijgil5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s1jmd4bmi"/><path class="haze59b4w"/><path class="zyijgil5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:posts-carousel-horizontal-outline" /></template>
