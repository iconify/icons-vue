<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxx8p7oda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxx8p7oda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:voiceprint-line" /></template>
