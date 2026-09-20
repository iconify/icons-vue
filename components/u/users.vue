<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtufn9bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtufn9bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:users" /></template>
