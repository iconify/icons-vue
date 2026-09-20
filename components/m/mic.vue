<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftmaetule.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftmaetule"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:mic" /></template>
