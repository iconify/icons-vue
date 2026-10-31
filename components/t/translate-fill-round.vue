<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y39qohbhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y39qohbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:translate-fill-round" /></template>
