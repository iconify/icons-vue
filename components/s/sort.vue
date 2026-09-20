<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i66y6ob-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i66y6ob-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:sort" /></template>
