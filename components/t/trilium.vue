<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewzfa94-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewzfa94-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:trilium" /></template>
