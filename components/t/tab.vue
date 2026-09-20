<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcuc76lyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcuc76lyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:tab" /></template>
