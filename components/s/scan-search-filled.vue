<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq0xx5q_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sq0xx5q_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:scan-search-filled" /></template>
