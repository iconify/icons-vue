<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij8x6pboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ij8x6pboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-fill-round" /></template>
