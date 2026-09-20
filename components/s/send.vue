<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohsi8t-cv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohsi8t-cv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:send" /></template>
