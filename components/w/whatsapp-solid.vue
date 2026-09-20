<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmv27jblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmv27jblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:whatsapp-solid" /></template>
