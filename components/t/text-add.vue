<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsb9exiyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsb9exiyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:text-add" /></template>
