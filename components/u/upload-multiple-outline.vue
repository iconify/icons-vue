<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz1_7bcny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jz1_7bcny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:upload-multiple-outline" /></template>
