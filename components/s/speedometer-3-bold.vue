<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk_5tesqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="vk_5tesqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:speedometer-3-bold" /></template>
