<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryps3tfse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryps3tfse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:paper-2-fill" /></template>
