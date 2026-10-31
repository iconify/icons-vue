<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmxmc5hjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmxmc5hjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:music-notes-fill-round" /></template>
