<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofecthzgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofecthzgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:post-it-note-search" /></template>
