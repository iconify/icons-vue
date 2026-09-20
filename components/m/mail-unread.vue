<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmb9oon6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmb9oon6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:mail-unread" /></template>
