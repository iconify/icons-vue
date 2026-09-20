<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd1gwzgly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd1gwzgly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:speaker" /></template>
