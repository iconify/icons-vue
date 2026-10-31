<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doc4uemle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="doc4uemle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pen-tool-round" /></template>
