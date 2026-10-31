<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8wlqkblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8wlqkblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-cursor-round" /></template>
