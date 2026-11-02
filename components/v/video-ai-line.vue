<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcblw9b_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcblw9b_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:video-ai-line" /></template>
