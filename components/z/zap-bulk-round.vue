<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1ie711_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1ie711_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-bulk-round" /></template>
