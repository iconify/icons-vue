<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1r-pxbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1r-pxbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:movie-ai-fill" /></template>
