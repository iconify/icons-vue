<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy0u-nfrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xy0u-nfrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:uv-index-alt" /></template>
