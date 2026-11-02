<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4ec4mghr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4ec4mghr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-square-check-fill" /></template>
