<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl7oi3wqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="wl7oi3wqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:mail-send-email-message" /></template>
