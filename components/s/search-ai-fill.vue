<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xylo4ccpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xylo4ccpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:search-ai-fill" /></template>
