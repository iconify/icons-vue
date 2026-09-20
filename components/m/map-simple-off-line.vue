<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6r0bob8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6r0bob8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:map-simple-off-line" /></template>
