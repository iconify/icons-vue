<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6-c51b7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6-c51b7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pencil-2-fill" /></template>
