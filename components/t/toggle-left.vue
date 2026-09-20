<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm5qftbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cm5qftbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:toggle-left" /></template>
