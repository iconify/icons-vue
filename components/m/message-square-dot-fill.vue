<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr-bp41ty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yr-bp41ty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-square-dot-fill" /></template>
