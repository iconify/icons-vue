<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es0czyb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="es0czyb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-ghost" /></template>
