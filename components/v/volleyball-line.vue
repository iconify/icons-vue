<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yobi60uah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yobi60uah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:volleyball-line" /></template>
