<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru3w11duv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru3w11duv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:search-ai-4-line" /></template>
