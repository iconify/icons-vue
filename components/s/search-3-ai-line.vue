<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua000itue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ua000itue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:search-3-ai-line" /></template>
