<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbc9os0zg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbc9os0zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paperclip-fill-round" /></template>
