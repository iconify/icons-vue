<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch78ytbft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch78ytbft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:openai-fill" /></template>
