<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsp6_lb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dsp6_lb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:trilium-notes-dark" /></template>
