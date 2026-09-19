<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxp_3lb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vxp_3lb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:toggle-on-fill" /></template>
