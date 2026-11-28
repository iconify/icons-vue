<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nop6pnbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nop6pnbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:receipt-text-solid" /></template>
