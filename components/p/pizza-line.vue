<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9x36qboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9x36qboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pizza-line" /></template>
