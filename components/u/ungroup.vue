<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dio5em1vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dio5em1vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:ungroup" /></template>
