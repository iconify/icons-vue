<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1t39q2tg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1t39q2tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:paper-fill" /></template>
