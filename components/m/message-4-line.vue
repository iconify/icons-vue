<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l64f97bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l64f97bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-4-line" /></template>
