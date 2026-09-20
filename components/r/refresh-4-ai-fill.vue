<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_h4t5b4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_h4t5b4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:refresh-4-ai-fill" /></template>
