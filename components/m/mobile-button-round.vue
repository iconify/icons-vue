<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk0loy1nx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vk0loy1nx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-button-round" /></template>
