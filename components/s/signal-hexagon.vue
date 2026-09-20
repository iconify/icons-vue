<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo64tablj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo64tablj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:signal-hexagon" /></template>
