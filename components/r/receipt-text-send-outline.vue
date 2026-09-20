<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmag5z49h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmag5z49h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:receipt-text-send-outline" /></template>
