<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukes7hl0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukes7hl0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:road-fill-round" /></template>
