<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3ecx8h6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3ecx8h6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:transmission-virus-human-transmit-2" /></template>
