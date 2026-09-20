<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzdfplffv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzdfplffv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:minus-box" /></template>
