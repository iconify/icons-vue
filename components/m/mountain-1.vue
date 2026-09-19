<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cot1lm0tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cot1lm0tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:mountain-1" /></template>
