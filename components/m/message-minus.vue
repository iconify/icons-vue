<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1cl0ac7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1cl0ac7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:message-minus" /></template>
