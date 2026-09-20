<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa25j04aq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa25j04aq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:message-reply" /></template>
