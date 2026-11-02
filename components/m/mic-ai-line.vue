<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs5be5bek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rs5be5bek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mic-ai-line" /></template>
