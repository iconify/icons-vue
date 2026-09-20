<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubw90kood.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubw90kood"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:notification" /></template>
