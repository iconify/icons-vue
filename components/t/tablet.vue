<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2f6oxbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2f6oxbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:tablet" /></template>
