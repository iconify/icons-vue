<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdgb0sbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdgb0sbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:notebook-fill-round" /></template>
