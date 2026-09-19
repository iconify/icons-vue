<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke08gvjmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke08gvjmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ram-memory" /></template>
