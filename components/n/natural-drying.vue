<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnwtfzb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnwtfzb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ginetex:natural-drying" /></template>
