<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx2k6dbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bx2k6dbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:widget-areaspline-variant" /></template>
