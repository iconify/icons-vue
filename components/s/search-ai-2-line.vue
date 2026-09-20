<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w36xbxbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w36xbxbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:search-ai-2-line" /></template>
