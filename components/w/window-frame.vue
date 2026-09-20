<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqgef37ge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqgef37ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:window-frame" /></template>
