<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd-tiacai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd-tiacai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:window-lock" /></template>
