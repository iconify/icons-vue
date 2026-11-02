<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drwwbympz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drwwbympz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:stock-fill" /></template>
