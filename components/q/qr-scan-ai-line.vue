<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oju0y9a-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oju0y9a-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:qr-scan-ai-line" /></template>
