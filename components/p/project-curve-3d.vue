<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydgc67bfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydgc67bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:project-curve-3d" /></template>
