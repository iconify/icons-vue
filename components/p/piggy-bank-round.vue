<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq1j11bcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xq1j11bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:piggy-bank-round" /></template>
