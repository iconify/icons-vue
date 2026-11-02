<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep1smqepr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ep1smqepr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:youtube-line" /></template>
