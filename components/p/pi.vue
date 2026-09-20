<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwz6ptbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vwz6ptbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:pi" /></template>
