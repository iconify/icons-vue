<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hefpc1big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hefpc1big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:question-answer-fill" /></template>
