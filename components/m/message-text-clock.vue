<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o11xs_bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o11xs_bqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:message-text-clock" /></template>
