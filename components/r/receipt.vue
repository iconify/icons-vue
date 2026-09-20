<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pedkxypgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pedkxypgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:receipt" /></template>
