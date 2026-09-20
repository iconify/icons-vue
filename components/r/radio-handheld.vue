<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej63n7c8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ej63n7c8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:radio-handheld" /></template>
