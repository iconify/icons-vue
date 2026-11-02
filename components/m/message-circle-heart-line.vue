<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_9zt_oer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_9zt_oer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-circle-heart-line" /></template>
