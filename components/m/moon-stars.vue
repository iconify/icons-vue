<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd03i40nu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fd03i40nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:moon-stars" /></template>
