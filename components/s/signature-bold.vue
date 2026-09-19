<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0ty2nbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="d0ty2nbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:signature-bold" /></template>
