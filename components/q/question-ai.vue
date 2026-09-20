<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caly64b0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="caly64b0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:question-ai" /></template>
