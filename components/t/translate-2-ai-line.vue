<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6iwfab2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6iwfab2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:translate-2-ai-line" /></template>
