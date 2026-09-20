<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb08p0b6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb08p0b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:suitcase" /></template>
