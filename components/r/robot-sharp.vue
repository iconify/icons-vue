<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-uq9dcxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-uq9dcxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:robot-sharp" /></template>
