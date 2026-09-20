<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp2_b80ur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zp2_b80ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:message-ai-3-fill" /></template>
