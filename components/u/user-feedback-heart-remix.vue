<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy6ocrb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yy6ocrb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:user-feedback-heart-remix" /></template>
