<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxb6k-z4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxb6k-z4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-2-ai-line" /></template>
