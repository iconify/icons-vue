<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yec8yv09h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yec8yv09h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:news-fill" /></template>
