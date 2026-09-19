<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw62veb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gw62veb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:sewing-needle" /></template>
