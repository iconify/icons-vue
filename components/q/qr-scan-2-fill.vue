<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erfu-kb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erfu-kb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:qr-scan-2-fill" /></template>
