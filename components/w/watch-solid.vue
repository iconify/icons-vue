<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjlvsp_ed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjlvsp_ed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:watch-solid" /></template>
