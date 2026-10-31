<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my5tmi8qa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="my5tmi8qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:superscript-fill-round" /></template>
