<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6jpejzjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6jpejzjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:news-2-line" /></template>
