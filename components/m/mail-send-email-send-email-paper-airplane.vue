<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtvj1dvjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="gtvj1dvjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:mail-send-email-send-email-paper-airplane" /></template>
