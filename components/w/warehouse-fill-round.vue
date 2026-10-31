<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqfz1qjfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqfz1qjfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:warehouse-fill-round" /></template>
