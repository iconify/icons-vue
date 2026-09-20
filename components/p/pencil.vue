<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7_1u4b4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7_1u4b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:pencil" /></template>
