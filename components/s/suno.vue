<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc3we9v5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc3we9v5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:suno" /></template>
