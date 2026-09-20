<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-7rukgbc.css';
import '../../css/l/lu1huab3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-7rukgbc"/><path class="lu1huab3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:send-email-paper-plane-1" /></template>
