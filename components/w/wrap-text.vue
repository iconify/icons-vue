<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9zy8wb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":368,"height":384};
const content = `<path class="x9zy8wb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:wrap-text" /></template>
