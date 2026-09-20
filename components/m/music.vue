<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zamm2dodg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zamm2dodg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:music" /></template>
