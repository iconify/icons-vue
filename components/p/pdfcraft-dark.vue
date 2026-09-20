<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5qv-l8kf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d5qv-l8kf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pdfcraft-dark" /></template>
