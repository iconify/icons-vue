<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxp4o7b8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxp4o7b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:presentation-round" /></template>
