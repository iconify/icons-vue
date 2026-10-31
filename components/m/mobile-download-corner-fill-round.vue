<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry0e54byo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry0e54byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-download-corner-fill-round" /></template>
