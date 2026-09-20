<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-2fixb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-2fixb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:qr-scan-ai-fill" /></template>
