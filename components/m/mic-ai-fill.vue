<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-lk-v-fe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-lk-v-fe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mic-ai-fill" /></template>
