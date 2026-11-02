<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn9e3pbdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xn9e3pbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:news-line" /></template>
