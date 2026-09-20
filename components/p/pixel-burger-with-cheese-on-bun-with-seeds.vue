<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq3zy8b4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fq3zy8b4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-burger-with-cheese-on-bun-with-seeds" /></template>
