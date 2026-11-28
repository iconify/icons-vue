<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p05y_u--y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p05y_u--y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:music-note-plus" /></template>
