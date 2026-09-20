<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tecw7fbzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tecw7fbzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:speech-line" /></template>
