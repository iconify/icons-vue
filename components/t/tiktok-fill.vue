<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwaubxgoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwaubxgoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:tiktok-fill" /></template>
