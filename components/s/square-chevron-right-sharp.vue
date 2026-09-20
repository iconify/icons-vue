<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfz9ytbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfz9ytbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:square-chevron-right-sharp" /></template>
