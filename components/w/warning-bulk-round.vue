<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlgb3ob_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlgb3ob_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:warning-bulk-round" /></template>
