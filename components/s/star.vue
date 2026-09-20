<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvsuz0qrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvsuz0qrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:star" /></template>
