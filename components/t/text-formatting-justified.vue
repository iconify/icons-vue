<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr_en4evr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vr_en4evr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:text-formatting-justified" /></template>
