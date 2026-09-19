<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i301vq99h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":384};
const content = `<path class="i301vq99h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:view-compact" /></template>
