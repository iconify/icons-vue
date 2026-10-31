<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_x04cbkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_x04cbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-close-corner-fill-round" /></template>
