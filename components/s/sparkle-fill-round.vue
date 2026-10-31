<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d82cjfbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d82cjfbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sparkle-fill-round" /></template>
