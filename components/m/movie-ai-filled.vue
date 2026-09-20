<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/niy991b9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="niy991b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:movie-ai-filled" /></template>
