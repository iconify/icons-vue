<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc85rwl1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc85rwl1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:zodiac-gemini" /></template>
