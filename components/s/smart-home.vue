<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7bpm2bqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7bpm2bqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:smart-home" /></template>
