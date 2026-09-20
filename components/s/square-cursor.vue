<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddn_7b-3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddn_7b-3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:square-cursor" /></template>
