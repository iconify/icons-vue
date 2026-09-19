<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7t_42bwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7t_42bwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:virus-lab-research-medicine-pill" /></template>
