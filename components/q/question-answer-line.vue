<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9d8fjder.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9d8fjder"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:question-answer-line" /></template>
