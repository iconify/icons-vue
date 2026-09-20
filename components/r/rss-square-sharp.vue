<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e60ttggyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e60ttggyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:rss-square-sharp" /></template>
