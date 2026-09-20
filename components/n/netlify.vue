<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lppvp4b4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lppvp4b4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:netlify" /></template>
