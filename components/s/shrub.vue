<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycx2subns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycx2subns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:shrub" /></template>
