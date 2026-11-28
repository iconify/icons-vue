<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb3t2lvkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb3t2lvkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:music-play" /></template>
