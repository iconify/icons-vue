<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbr2rikas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbr2rikas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:x-solid" /></template>
