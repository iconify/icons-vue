<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzyklx2ws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzyklx2ws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:zoom-in" /></template>
