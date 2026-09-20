<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbmh4p5by.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbmh4p5by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:music-2-fill" /></template>
