<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5kfyacps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5kfyacps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:nurse-line" /></template>
